# ML_SMS_Classifier_XWA
SMS Text Classifier based on machine learning


#  <span style="color:blue">Overview  </span>
#### <span style="color:blue">1) Presettings </span>
#### <span style="color:blue">2) Visualisation of Raw Data </span>
#### <span style="color:blue">3) Data Preprocessing </span>
- Most frequent words 

      - Bar Chart                   [done]
        
      - Pie Chart                   [done]
        
      - Word Cloud                  [done]
        
      - Heat Map                    [ToDo]
      
- Split total messages

- Creating Embedding Matrix from data 

      - BoW                         [done]
    
      - Word2Vec                    [ongoing]
    
      - BERT                        [ToDo]
      

#### <span style="color:blue">4) Building and evaluating models </span>
    - Logistic Regression             [done]


    - Naive Bayes MultinomialNB       [done]


    - Support Vector Machine          [done]
    
    
    - Random Forest                   [done]


    - Deep Neural Networks            [ToDo]


    - Convolutional Neural Networks   [ToDo]


    - Recurrent Neural Networks       [ToDo]




#### <span style="color:blue">5) Comparing models </span>
#### <span style="color:blue">6) Model optimization  </span>

#### Further steps [ToDo]
###### - Automatic Hyperparametervariation - XWA-05.11.21
###### - Building pipelines from data preprocessing - XWA-06.11.21
###### - Word2Vec via tok2 -XWA-03.11.21
###### - BERT - XWA-03-11-2021
###### - Word2Vec via tok2 -XWA-03.11.21

## Schritt 1
nltk.download('all') 

## -------- Further steps in Anaconda Prompt --------

## Step 2
## NOTE: update your gensim for Word2Vec functionality via Anaconda Prompt
## conda install gensim

## Step 3
## NOTE: install wordcloud for display functionality via Anaconda Prompt
## conda install -c conda-forge wordcloud

## Step 4
## NOTE: install tensorflow version 2.3.0 via Anaconda Prompt
## conda install -c conda-forge tensorflow tensorflow==2.3.0


## Step 5
## NOTE: install keras via Anaconda Prompt
## conda install -c conda-forge keras

## Step 6
## NOTE: install plotly via Anaconda Prompt
## pip install plotly
