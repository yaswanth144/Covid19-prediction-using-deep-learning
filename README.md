# Covid19-prediction-using-deep-learning
# link for dataset 
https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets
# About the dataset
The dataset can be found from above given link.It contains two directories train and test with images of lungs for checking pneumonia.
# Steps in detecting covid19 virus
I am using Kaggle kernel.You can use colab or Jupyter notebook.

1.Import necessary Libraries.

2.Load train and test images.

3.Use Image data generator for normalizing,zooming e.t.c for  all images of train and test images

4.Do data Augumentation.

5.Create a CNN Model,compile and fit the train data by giving test data as validation data.

6.visualise training loss and validation loss.

7.Repeat steps 5 and 6 until you get good visualisation of training and validation loss(i.e. both losses are nearly equal preventing from both overfitting and underfitting).


