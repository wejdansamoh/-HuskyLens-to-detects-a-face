Using Arduino to Switch ON an LED When HuskyLens Detects a Face project . 



The objective of this project is to use an Arduino  and a HuskyLens AI machine vision sensor to switch on an LED when a face is detected. 

The HuskyLens is capable of facial recognition and communicates with the Arduino via the I2C protocol.

Components

Arduino 

HuskyLens AI Machine Vision Sensor

LED

Jumper wires

Breadboard

Steps

Setup the Hardware:

Connect the HuskyLens to the Arduino  using I2C protocol:

HuskyLens SDA to Arduino Mega SDA (pin 20)

HuskyLens SCL to Arduino Mega SCL (pin 21)

Connect the LED to pin 7 of the Arduino  

Ensure all ground (GND) connections are made to complete the circuit.


Download and install the HuskyLens library from the DFRobot website or via the Arduino Library Manager.



This project successfully demonstrates the integration of the HuskyLens AI machine vision sensor with an Arduino Mega to perform a simple task of switching on an LED when a face is detected. This can be a foundational step towards more complex applications involving facial recognition and automated responses.
