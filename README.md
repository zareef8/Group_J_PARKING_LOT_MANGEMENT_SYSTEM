# Group_J_PARKING_LOT_MANGEMENT_SYSTEM #

The software program is a parking lot management system which will help parking lot owners to manage thier lots effectively and efficiently. 

# Organization #
Carleton Univeristy & University of Ottawa

# Authors #

  * Arif Rubayet 
  
  * Christopher Owoicho  

  * Michael Schrier 
 
  * Zareef Al Islam 

# Brief Description #
The program consists of features for both an Admins and the Clients of the parking lot. 
The program keeps records of all the vehicles entering and exiting the parking lot at all times. 
The current status of the parking lot can be seen i.e The number of spots left. 
There is an automatic calcualtion of the payment based on the system time.
Admins of the lot can login using a password and will be able access features like blacklisting vehicles,searching vehicles,Display vehicle information,etc.
Admis can also see certain reports for the parking lot like: The average time parked, the standard deviation and displaying vehicles fot the last 30 days.
More infornmation about the features and how to use them is given in the Usage section.

# File Organization  

![directiryyy](https://user-images.githubusercontent.com/71241275/102732806-a95ad100-4309-11eb-9551-f4622550f91c.jpg)


# Installation # 

### Download Cygwin
To run the code you must download cygwin, have a GCC Compiler and GNUmake

You can download and install cygwin from here : https://cygwin.com/install.html

### Download code files

The code can be downloaded from the github repository: https://github.com/zareef8/Group_J_PARKING_LOT_MANGEMENT_SYSTEM

Open the cygwin terminal and change the directory to the folder where the files are stored

![changedirruncode](https://user-images.githubusercontent.com/71241275/102730737-ad83f000-4303-11eb-8b32-361cabbcba17.jpg)

Then type in the command to compile and run the main program in the terminal

```
make runcode
```

![qqqqqqqqqqqq](https://user-images.githubusercontent.com/71241275/102737215-cba61c00-4314-11eb-980e-8d6e2b77fb71.jpg)




For the test program type in the following command to compile and run it in the terminal

```
make runtest
```

After running the step by step instructions are given in the User Manual. Please make sure that the data.txt file is not removed from the /bin folder.

# Usage #

After successful compilation the program is ready to use. The step by step user manual can be found here : https://github.com/zareef8/Group_J_PARKING_LOT_MANGEMENT_SYSTEM/wiki/User-Manual

User Manual for testing the software can be found here:https://github.com/zareef8/Group_J_PARKING_LOT_MANGEMENT_SYSTEM/wiki/User-Manual--For-Testing

Instrucitons for developers can be found here: https://github.com/zareef8/Group_J_PARKING_LOT_MANGEMENT_SYSTEM/wiki/Developer-Guide

# Assumptions #
* The program will be used for a parking lot that can hold 100 vechicles
* The program will be used for parking lots with a parking fare of 10 dollars per hour
* The system time will always be accurate which is directly taken only from the system.
* There is no force shutdown of the program 
* Customers and admins are entering the correct information where they are required to.

# License 
 [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
