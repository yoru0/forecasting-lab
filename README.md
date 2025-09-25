# Forecasting Lab

A machine learning project that uses Long Short-Term Memory (LSTM) neural networks to predict stock and cryptocurrency prices. This project demonstrates time series forecasting using TensorFlow/Keras with Bitcoin (BTC-USD) as the default example.

## Features

- **Time Series Prediction**: Uses LSTM networks to forecast stock/crypto prices
- **Data Visualization**: Comprehensive exploratory data analysis with matplotlib and seaborn
- **Model Evaluation**: Multiple metrics including MSE, MAE, RMSE, and R² score
- **Real-time Data**: Fetches live data using Yahoo Finance API
- **Configurable Parameters**: Easy to adjust lookback window, epochs, and other hyperparameters

## Model Architecture

The LSTM model consists of:
- **Input Layer**: Sequences of 100 previous days
- **LSTM Layer 1**: 128 units with dropout (0.2)
- **LSTM Layer 2**: 64 units with dropout (0.2)
- **Dense Output**: Single neuron for price prediction

## Model Performance

The model includes several evaluation metrics:
- **MSE**: Mean Squared Error
- **MAE**: Mean Absolute Error
- **RMSE**: Root Mean Squared Error
- **R² Score**: Coefficient of determination

## Dependencies

Key libraries used:
- TensorFlow/Keras for deep learning
- yfinance for financial data
- pandas/numpy for data manipulation
- matplotlib/seaborn for visualization
- scikit-learn for preprocessing and metrics
