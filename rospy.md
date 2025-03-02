# ros

- Tao khong gian lam viec:
```
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
catkin_make
```

- Tao 1 package ROS moi:
```
cd ~/catkin_ws/src
catkin_create_pkg <ten-package> <cac-goi-message>
cd <ten-package>
```

- Tao file Python:
```
mkdir scripts
cd scripts
code <ten-file>.py
```

- Cap quyen thuc thi cho file:
```
chmod +x ~/catkin_ws/src/<ten-package>/scripts/<ten-file>.py
```

- Build package:
```
cd ~/catkin_ws
catkin_make
source devel/setup.bash
```

- Chay chuong trinh:
  - Terminal 1:
  ```
  roscore
  ```

  - Terminal 2:
  ```
  rosrun turtlesim turtlesim_node
  ```

  - Terminal 3:
  ```
  rosrun <ten-package> <ten-file>.py
  ```
