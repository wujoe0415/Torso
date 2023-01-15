# Torso

## Features

+ Transform Parenting System
+ Render 3D Object

### Demo

<img src="C:\Users\wujoe\AppData\Roaming\Typora\typora-user-images\image-20230116031728347.png" alt="image-20230116031728347" style="zoom:50%;" />

<img src="C:\Users\wujoe\AppData\Roaming\Typora\typora-user-images\image-20230116031707267.png" alt="image-20230116031707267" style="zoom:50%;" />

### Compile

Copy the command below and paste on command line.

```shell
g++ -g -std=c++17 -I ./include -L ./lib -I ./src/"Game Logic" ./src/"Game Logic"/"Basic Logic"/*.cpp ./src/"Game Logic"/"System"/*.cpp main.cpp -o main -lglad glfw3.dll
```

### Input

You can adjust part by pressing **Rotation axis button** and **Part number button** simultaneously.
+ Rotation axis button
	- X : rotate around x-axis
	- Y : rotate around y-axis
	- Z : rotate around z-axis
+ Part number button
	- 1 : Head
	- 2 : Upper left arm
	- 3 : Lower left arm
	- 4 : Upper right arm
	- 5 : Lower right arm
	- 6 : Upper left leg
	- 7 : Lower left leg
	- 8 : Upper right leg
	- 9 : Lower right leg