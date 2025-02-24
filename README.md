# classification_challenge
Homework 13 | Machine Learning - Logistic Regression Classification


**Classification Challenge**

## Table of Contents
* [Introduction](#introduction)
* [Installation Requirements](#requirements)
* [Usage](#usage)
* [License](#license)
* [Acknowledgement / Contributing](#acknowledgementcontributing)

## Introduction
This project is the thirteenth coding module challenge that we had to complete as part of the Denver University AI Bootcamp coursework. 

The initial code provided for the challenge had us work with a CSV file for features that could be used to identify a message as spam (eg. character types, frequency, word count, etc) ingest it and then use a Logistic Regression and a Random Forest Classifier models to fit, score, and predict and compare the accuracy of the two models. While a Logistic Regression is computationally faster and requires less training, the Random Forest performed better than a Logistic Regression, as a random forest is going to involve multiple decision trees / paths to reach a prediction and can provide importance feature analysis, helping us identify the feature(s) most likely to influence the target. The *rfcl_features = rfcl_model.feature_importances_* was also used to identify the specific features that most influenced the model as well. 


## Installation Requirements
*Requirements*: You must run Python 3.12.7 to execute the code as the code uses match case sytax that is older versions of python will not recognize.

## Usage
For those trying to understand how to train, and build the two models (Logistic Regression / Random Forest Classifier) to perform predictions on datasets.  

## License
I've included the MIT License to encourage collaboration and use by the community.

## Acknowledgement / Contributing
Thank to the guidance of the Denver University AI Bootcamp Teachers Assistant's and their hints via comments that helped me complete this assignment. Without this I would've been completely lost. 

While a section of this code was written by the Denver University AI Bootcamp Teachers Assistant, it has been modified / completed by me. 

