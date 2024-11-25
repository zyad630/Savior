Project Overview
This project involves the development of a drone system designed to detect survivors under debris using thermal imaging, GPS, and sound sensors. The drone identifies heat signatures, pinpoints locations using GPS, and transmits real-time data to rescue teams to facilitate faster response times in disaster areas.

AI Model Description
Type: Thermal image processing, sensor data fusion.
Purpose: To detect human heat signatures and locate survivors under rubble.
Key Features: Real-time location tracking, human detection using thermal sensors, GPS integration for precise positioning.

Dataset Used and Preprocessing
Dataset: Synthetic thermal images simulating human and non-human heat sources, GPS data from simulated rescue missions.
Preprocessing: Normalization of thermal images for better detection accuracy, thresholding for object detection.

Model Performance
Metrics: Detection accuracy of 90%, response time under 5 seconds for transmitting location data.
Results: The drone successfully detects and locates people under debris, transmitting the coordinates and heat signature for timely rescue efforts.

Code Organization
The project code is structured with clear separation between sensor data acquisition, image processing, and communication handling. The code is organized into multiple files for easy understanding and execution. The system uses an Arduino IDE for sensor integration and Python for data processing and communication.