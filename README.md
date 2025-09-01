## Movie Revenue Prediction Model ##

A machine learning project that predicts movie box office revenue based on production features using Random Forest regression.

## Results ##
- R² Score:0.85 (85% of revenue variation explained)
- Mean Absolute Error:** $25 million 
- Top Features: Budget, Popularity, Genre
- Best Model: Random Forest Regressor

## Quick Start ##


# Clone repository
git clone https://github.com/zad88/movie-revenue-predictor.git
cd movie-revenue-predictor

# Install dependencies #
pip install -r requirements.txt



## Project Structure ##
movie-revenue-predictor/
├── notebooks/           # Jupyter notebook with complete analysis
├── data/               # Dataset directory (from Kaggle)
├── requirements.txt    # Python dependencies
└── README.md          # Project documentation


## Dependencies ##

Python 3.8+
pandas,
numpy,
scikit-learn
matplotlib,
seaborn
jupyter

# Dataset #
TMDB 5000 Movie Dataset from Kaggle: Contains 5000 movies with features like budget, revenue, genres, ratings, and popularity.