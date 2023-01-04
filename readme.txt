Reiforcement Learning Double Q-Network DQN Project

Description: CS138 Group Project - Double Q DQN Model Performance on Breakout
Date Created: 12/01/2022
Python Environment: 3.6 above

"trained-model" folder includes the trained two NN and output model. 
"output" folder includes the ouput graphs for trained and evaluation.
"train_dqn.py" is the main DQN model py file.
"config.py" is the configuration file for "train_dqn.py".

MarsExplorer API Manual:https://github.com/dimikout3/MarsExplorer

MarsExplorer API Installation:
$ git clone https://github.com/dimikout3/GeneralExplorationPolicy.git
$ pip install -e mars-explorer

Following are the package needed for this project:
import numpy
import random
import os
import json
import time
import cv2
import gym
import tensorflow
tensorflow.keras.initializers
tensorflow.keras.layers 
tensorflow.keras.optimizers 
tensorflow.keras.models 
