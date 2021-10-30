# embedded systems projects :

   
## [Project 1: watering cattles controlled system ](https://github.com/ysfelkantri/embedded_soft_project) 

**About** : a prototype of a controlled system to solve the problem related to the watering of dairy cows

Included in the field of precision agriculture, this project aims to produce a prototype of a controlled system capable of automating the watering of dairy cows in buildings, based on the client-server architecture, a fairly interesting whose main assets are:
* The server allows to acquire the values of the water level in the tank periodically.
* The server stores the values collected by the sensors in a database.
* The web interface allows manual control of the pump.
* The web interface allows monitoring of the system status in real time.
* The web interface displays information on daily water consumption.

#### objectives of this system :
* Have a controlled system for watering dairy cows without human interaction.
* Placing a sensor capable of measuring the water level in the field allows farmers to establish a detailed map of the water level in the reservoir.
* Have access to data related to weekly consumption, which allows you to anticipate trends for the days and weeks to come.
* Create new business opportunities thanks to freed up time

![](/client_server_architecture.png)
##### [DOCUMENTATION(Francais)](https://github.com/ysfelkantri/embedded_soft_project/blob/master/rapport_Systeme_asservi_d_abreuvement_des_vaches_laitieres.pdf)

## [Project 2: data logger server](https://github.com/ysfelkantri/data_logger_server)

**About** : Collaborating on creating a controlled system to read from sensors using modbus protocole and raspberry pi 4 as a server 


we used the raspberry pi as a server because it allows to connect several serial port slaves, using _Modbus_ data communications protocol with RTU frame format, used on asynchronous serial data lines _RS-485_, for the backend we used django framework and the celery server to execute some background tasks with a specific periodicity

we have created this system using a master/slave architecture a solution that provides :
* ***Centralized resources*** : given that the server is at the center of the network, it can manage resources common to all users, such as the centralized database, for example, in order to avoid redundancy problems and contradiction
* ***Better security*** : because the number of entry points allowing access to data is less important
* ***A scalable network*** : thanks to this architecture it is possible to remove or add clients without disturbing the functioning of the network and without major modification

## [Project 3: Smart Irrigation ](https://github.com/ysfelkantri/Smart_irrigation) 

**About** : Collaborating on an edge computing system app related to precision farming field that collects information to monitor plants, intervenes for agricultural management, supervise the irrigation system in real time and automatically guide this process.
*  the system is easy to handle without any special knowledge of computer or electronics.
*  the system is designed in such a way that we can modify it without having to redo all the work.
*  the system can be adapted to other cases and application situations which are part of "smart irrigation".  

The entire system is powered by an electrical system ensuring optimal energy consumption. In his mobile / web application the user will be able to monitor this energy consumption.
The irrigation system is therefore essentially based on:
* The implementation of networks of communicating sensors and actuators,
* The implementation of an on-board Raspberry control / command platform to collect information from sensors and monitor the system remotely.
* The implementation of appropriate software in the embedded systems under a C, Python and Linux environment.
* Client / server communication via remote communication protocols and mobile / web applications.


## [Project 4: graphic interface with Matlab GUIDE for An App of Compressing data](https://github.com/ysfelkantri/graphic-interface-with-Matlab-GUIDE-for-An-App-of-Compressing-data)

this an application where we use matlab the backend and the front end to create an application to compress data using Huffman et Shanon-fano Algorithms then calculate the compression ratio for text, and performing the best methode (horizontal, vertical or zigzag) to read an image:

![](/codage.png)
##### [DOCUMENTATION(Francais)](https://github.com/ysfelkantri/data_coding_App/blob/main/EL_KANTRI_Youssef_GSEII2_compte_rendu_GUIDE_App.pdf)

# artificial intelligent projects :

## [Project 1: Training of a multi-sensor system for Covid-19 detection on existing thermal images ](https://github.com/ysfelkantri/CNN_CIFAR10) 

Report whose primary objective is to present the activities of an internship at the SIGERLaboratory.   It includes the tools and the approach that can be used to fight Covid-19 using  artificial  intelligence. This  project  is  the  result  of  a  two-months  research  and hard  work  at  the  SIGER  Laboratory  in  Fez,  in  order  to  validate  my  second  year  of engineering cycle in embedded systems. The experience, relationships and interventionsof  my  internship  supervisors  have  been  very  useful  to  reframe  a  study  whose  scopeis very wide.  I wanted to study a topical and still little explored subject:  " Training of a multi-sensor system for Covid-19 detection on existing thermal images".   The choiceof  the  subject  is,  in  fact,  directly  related  to  the  recent  news  with  the  announcementmade  by  the  World  Health  Organization  on  the  danger  of  this  virus  and  how  it  hasparalyzed  the  world  economy.The  SIGER  Laboratory  is  specialized  in  innovativeresearch and therefore allowed us to study this trend closely and try to find a solution tofight against this virus .  Our subject proposes a solution based on artificial intelligenceand  machine  learning  to  predict  whether  a  person  has  the  covid-19  or  not  based  ontemperature, cough and respiratory rhythm which will be collected by a thermal cameraand  microphones.   For  the  training  of  the  model  we  used  an  artificially  created  dataset  while  waiting  to  have  the  real  data  set,  for  the  training  algorithm  we  decided  touse the SVM and random forest because they give good results on classification problems

![](/SVM_RF.png)
##### [DOCUMENTATION(Francais)](https://github.com/ysfelkantri/Entrainement_d-un_systeme_multi-capteurs_pour_la_detection_du_COVID-19/blob/master/Rapport_de_stage_d-application_sujet5.pdf)

## [Project 2: Image Classification Using Convolutional Neural Network CNN ](https://github.com/ysfelkantri/CNN_CIFAR10) 

**About** : The purpose of this project is to look at CNN architecture, and test its performance on the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) Dataset.

a classification approach based on convolutional neural networks , This project is divided into 4 parts: 
*  Loading and displaying cifar-10 dataset 
*  Pre-processing dataset 
*  Building the model 
*  Testing the model

for this we used a model with a specified architecture and we showed the different results obtained in terms of precision and error. The analysis of the results found has shown that the CNN is a very powerful way to classify image since it gives very high accuracy (86%) and low error.

![](/CNN_model_accuracy.PNG)
##### [DOCUMENTATION(English)](https://github.com/ysfelkantri/CNN_CIFAR10/blob/master/documentation/projet_CNN_Rapport_IA-LV.pdf)

## [Project 2: Arrow Detection classifier (convolutional neural network model)](https://github.com/ysfelkantri/Arrow_Detection)

**about** : A model to detect arrow's direction using Convolutional Neural Network classifier.

it can be used to orient a robot in its way by reading the arrow's direction to follow, up down left and right.
this model can even predict images that has not seen before with very high probability which reflect the power of CNN models in classifying images.

## [Project 3: Movie Recommender System (Machine learning project)](https://github.com/ysfelkantri/systeme_de_recommandation_des_films)

**about** : Collaborating for improving a movie recommendation system using artificial intelligence under python

we have improved a system for recommending films. The goal of the system is to provide accurate movie recommendations to users. Typically, basic recommendation systems consider one of the following factors to generate recommendations:

* user preference (i.e. based on content filtering)
* the preference of similar users (collaborative filtering, for example). To build a stable and precise environment The recommendation system used in this project is based on element-based collaborative filtering (in this case movies).
##### [DOCUMENTATION(English)](https://github.com/ysfelkantri/systeme_de_recommandation_des_films/blob/master/Rapport_PROJET1_IA.docx)

# website projects :

## [Project 1: food manager website ](https://github.com/ysfelkantri/food_web_site) 

**About** : Collaborating on creating a website using HTML, CSS, JavaScript, Bootstrap, PHP, MySQL database and [spoonacular API](https://spoonacular.com/food-api/docs).
*  The idea behind this web-site is to manage foods combining restaurant meals and cooking at home to help you find and organize restaurant:
      - find recipes to use ingredients you already have ("what's in your fridge" search)
      - find recipes based on nutritional requirements
      - manage your favories list. 
*  We automatically analyze recipes to check for ingredients that contain common allergens, such as wheat, dairy, eggs, soy, nuts, etc. We also determine whether a recipe is vegan, vegetarian, Paleo friendly, Whole30 compliant, and more.
*  We compute the nutritional information for recipes automatically using a proprietary algorithm. With this information, you can find individual recipes or even create entire meal plans that satisfy your users' dietary goals.

#  game projects :

## [Project 1: Flappy Man (2D Game - Java Swing)](https://github.com/ysfelkantri/Flappy_Man)

**about** : Developing a 2D game using Java Swing Graphical interface and MYSQL database 

##### Game play 
Flappy Man is an arcade-style game in which the player controls the superman, which moves persistently to the right.
The player is tasked with navigating superman through pairs of pipes that have equally sized gaps placed at random heights.
superman automatically descends and only ascends when the player taps the touchscreen.
Each successful pass through a pair of pipes awards the player one point.
Colliding with a pipe or the ground ends the gameplay. During the game over screen, the player is awarded a bronze medal if they reached 3rd place,
a silver medal for 2nd place and a gold medal if the 1st place is reached.

![](/flappy_man.png)









