# -TV_News_Commercial_Detection
### Data:
The news channel TV News advertisements are variations of video shots that are distinctly
distinguished by audio-visual presentation. For TV commercial classification, the dataset
consists of different audio-visual features derived from video shots that are commonly used. It
consisted of 150 hours of videos from 5 different news channels broadcasting news. The
dataset consists of 205 functions and approximately 130,000 observations.

### Problem: 
Our aim is to build a classifier to predict whether a given segment of audio/visual features
from TV video stream data is a commercial or non-commercial. Automatic detection and
extraction in telecast news videos of commercial blocks is an important pre-processing step in
broadcast media analysis for competitive market analysis. News channel do not follow any
presentation format, through this classifier we will generalize features across different news
channels.

### Goals:
To distinguish commercial segments from non- commercial ones using audio/video features
extracted from content shown in the news channel. This could help news channels to
enhance advertising strategies as well as help them to show relevant content.

### Models and Interpretations:
We have performed data pre-processing, exploratory data analysis, feature engineering &
dimensionality reduction, selection of optimal learning algorithm for this problem with
hyperparameter tuning. We created Logistic Regression, Random forest model and Gradient
Boosting model to surmise if an audio-visual segment is commercial or non-commercial. We
also performed hyper-parameter tuning on Logistic Regression, Random forest model and
Gradient Boosting model to improve the accuracy.

The best model chosen is Gradient Boosting with highest accuracy of 94.5%. By using Gradient
Boosting, False positive rate got reduced as compared to Logistic Regression and Random
Forest models.

### Objectives Accomplished:
Using our model media organizations will be able to classify if a video is "Commercial" or "NonCommercial" manual. The information available to us was raw and had a great deal of missing values and outliers. Those had to be recognized and cleaned until it was appropriate for research
to be used (program outcome 2). Further being able to effectively improve its advertising and
broadcasting strategy, we used our data science knowledge to successfully build a classifier. This
would help achieve the desired objective of automated classification of TV
commercials.(program outcome 4 and 5)
