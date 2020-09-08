# Facial-Expression-Detector

### Introduction
This repository contains a facial expression detection model build using Keras API on [FER 2013 dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). 
Along with the model there's a flask web application (courtesy [Video_Streaming_with_Flask_Example](https://github.com/log0/video_streaming_with_flask_example)) using which one can put host this locally for real time predictions.  

### How to use?
1. Install dependencies using pipenv with the provided Pipfile and execute all commands using pipenv. 
2. Make sure to add the correct path to the video file in camera.py on line 11.Currently it is set on 0 i.e. inbuilt camera for real time recognition. 
3. Install pipenv, the dependencies, and run the main.py file.

4. Execute the following commands from your terminal or command prompt, making sure to add the right paths where necessary:

- cd \path\to\FER\
- pip install pipenv
- pipenv install
- pipenv run python3 main.py

5. Open web-browser and type `0.0.0.0:5000` to launch the web application. 



Special Thanks to Coursera for helping me build this model.
