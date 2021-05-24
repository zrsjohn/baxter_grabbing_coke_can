# baxter_grabbing_coke_can
#Summary
This is the code to put the baxter robot picking a coke can on the table in the simulation.The baxter robot use the right arm to pick the coke can
#quickstart
If you have installed the ROS ,ubuntu , the learning_ros_noetic package adn the learning_ros_external_pkgs_noetic from respected github user rojas70,you could just use the file object_grabber ,object_finder ,the rethink_electric_gripper xarco and the right_end_effector.urdf file to replace the original file dowmloaded from rojas70.You could simply start the coke can picking by baxter simulation.
#Overview
It is a simulation of baxter robot to pick one object at a time(this case is a coke can) in automation condition.
#videolink:
The video link is https://www.youtube.com/watch?v=YlkPXmVDtyk
FAQ:
Everybody could start the code like :
roslaunch baxter_gazebo baxter_worlds.launch
roslaunch exmpl_models add_cafe_table.launch
roslaunch exmpl_models add_coke_can.launch
roslaunch baxter_launch_files baxter_object_grabber_nodes.launch
rosrun object_grabber example_object_grabber_action_client
