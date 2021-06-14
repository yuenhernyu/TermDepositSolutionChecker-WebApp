# Validate Your ML Model Performance on Term Deposit Dataset from Kaggle

### This repository contains all the files for a ML prediction-checking web app.

**Try it now**:\
<a href="https://share.streamlit.io/yuenherny/termdepositsolutionchecker-webapp/main/webapp/streamlit_app.py">
<img src="metadata/clickhere.png" width="90>
</a>

## Credit to:
1. [**Brajesh Mahopatra**](https://github.com/brajeshmohapatra) for the dataset hosted on Kaggle.

2. [**The Streamlit team**](https://streamlit.io/) for the Streamlit framework and for making Python deployment easier.

## How to use this web app

1. Download the [Term Deposit Prediction Dataset](https://www.kaggle.com/brajeshmohapatra/term-deposit-prediction-data-set)
from Kaggle. In the dataset, there are several files:
   - `train.csv`: A CSV dataset containing the instances for training your ML model (with labels).
   - `test.csv`: A CSV dataset containing the instances for testing your ML model (without labels).
   - `solution_checker.xlsx`: A Excel file for you to check the performance of your ML model locally.
    
2. Train your model using `train.csv`.

3. Predict with your model using `test.csv`. Your output should be a `.csv` file with no column headers, and contains 
   13,564 instances.
   
4. Go to the [web app](https://share.streamlit.io/yuenherny/termdepositsolutionchecker-webapp/main/webapp/streamlit_app.py)
and upload your prediction `.csv` file at the sidebar.
   
5. Check your prediction results - accuracy, precision, recall and F1-score.

6. Share your work with the world!



<hr style="border:1px solid"> </hr>
<p align="center">
   <b>END</b>
</p>
<hr style="border:1px solid"> </hr>