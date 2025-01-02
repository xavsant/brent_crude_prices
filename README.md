# Forecasting Brent Crude Oil Prices

## Description

Practice with the Long Short-Term Memory (LSTM) model with a focus on physical energy commodities. 

In this project, I am interested in experimenting with LSTMs as their ability to handle sequential data allows them to analyse long-term dependencies between time steps of data. I am also interested in comparing LSTM vs other models.

This project is inspired by this [article](https://medium.com/@vinayarun/from-scratch-an-lstm-model-to-predict-commodity-prices-179e12445c5a) on forecasting commodity prices using an LSTM model. 


## Dependencies

#### **Exporting Dependencies**
If any packages/dependencies are updated via poetry, be sure to export the requirements.txt using the following:
`poetry export --without-hashes -f requirements.txt -o requirements.txt`

#### **Installing Dependencies**
Run the following the your command line:
`pip install -r requirements.txt`


## LSTM Results

- Validation Plot
![Validation Plot](visuals/lstm_validation_plot.png)

- Actual vs Predicted Plot
![Actual vs Predicted Plot](visuals/lstm_actual_vs_predicted_plot.png)
