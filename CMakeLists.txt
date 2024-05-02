cmake_minimum_required(VERSION 3.8)
project(rosshow)

find_package(ament_cmake REQUIRED)
find_package(ament_cmake_python REQUIRED)
find_package(std_msgs REQUIRED)
find_package(sensor_msgs REQUIRED)
find_package(rclpy REQUIRED)

ament_python_install_package(rosshow)

ament_package()
