# Capstone_Project
A shared repo
## Communication Protocol
We established a group chat in Slack so that we can maintain constant contact with each other. We use this to share links, ideas, and share comments and concerns. In addition, we have a shared google slides link that we use to brainstorm ideas and answer questions regarding the rubric.
## Link to Google Slides Presentation
https://docs.google.com/presentation/d/1DSq2EQ9AHUXf6Mmc_AwmwmjLqB2UXpBOd--rOGcSHMQ/edit#slide=id.p
## Project Outline
### Purpose
For our analysis, we are analyzing a dataset of potential factors that can lead to cardiovascular disease. We chose this topic because it could potentially help people. We wanted to do something that felt important and could be a benefit to society. Heart disease is a serious issue that potentially affects a large number of people. In fact, Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. People who are at risk need early detection and management. This where a machine learning model can be greatly beneficial. We hope that our analysis and observations can at least help with this issue.
### Description of Source of Data
Our dataset was found on kaggle. This dataset was created by combining five other datasets based on eleven common features. The five datasets used were Cleveland, Hungarian, Switzerland, Long Beach (VA), and the Stalog heart dataset. This is currently the largest heart disease dataset currently suitable for analysis.
### Questions We Hope to Answer
Heart failure is a common event caused by CVDs (Cardiovascular diseases) and this dataset contains 11 features that can be used to predict a possible heart disease. The main question we want answered is whether a person is likely to have a heart disease that can lead to heart failure. In order to find this out, we want to get more specific insights into which features play the biggest roles in heart diseases. For example, what are the top three features from the dataset in showing a correlation to CVDs? In contrast, which three features contribute the least to heart diseases? Is heart failure more of a concern in males or females? How much of a risk factor is age? Which age ranges are most susceptible to CVDs and heart failure? What is the disparity in people who experience normal angina with those who only experience exercise-induced angina? What role does this disparity play in possible heart failure?
### Data Exploration Phase
The dataset we found from Kaggle was largely cleaned before we got a chance to use it. There were no duplicate rows. There were no missing or null values. There were missing values in the cholesterol column but they were already changed to zeros. In addition, no datatype conversion was necessary.
### Analysis Phase
### Technologies, Languages, Tools, and Algorithms Used
We used a variety of tools, languages, technologies and algorithms to accomplish our task. We used Jupyter Notebook and Pandas to load our dataset into a dataframe in order to look at and clean the data. For the machine learning aspect, we used a handful of sklearn modules such as train_test_split, StandardScaler, OneHotEncoder, accuracy_score, LogisticRegression, and SVC. We also used Tensorflow. We used mongoDB for our database and we used Tableau to create the visualizations.
