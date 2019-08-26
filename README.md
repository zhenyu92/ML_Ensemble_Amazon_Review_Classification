# A study on Amazon Review Classification using Random Forest.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
Dataset consists of 3000 Amazon customer reviews, star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots.
The objective is to discover insights into consumer reviews and perfrom sentiment analysis on the data.

`Predictors:`
```
rating
date
variation
verified_reviews
```

`Target:`
```
Feedback (1: Good, 2: Bad)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_Random_Forest_Amazon_Review_Classification/blob/master/amazon_alexa.tsv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Random_Forest_Amazon_Review_Classification/blob/master/Decision%20Trees%20for%20Amazon%20Reviews%20Classification.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Exploring the Variables
      3.2 Visualizing the Variables
      3.3 Data Cleaning
    4 Train Test Split
    5 Select and Train a Model
      5.1 Random Tree Model
    6 Apply Model on Test Set
    7 Improve the Model
    ```   

### Model Performance
The model has an average `Precision` and `Recall` of 94%.
![alt text](https://github.com/zhenyu92/ML_Random_Forest_Amazon_Review_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
