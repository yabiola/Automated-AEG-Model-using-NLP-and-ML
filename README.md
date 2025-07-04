# Automated Essay Grading using NLP and Machine Learning methodologies project
Automated essay grading (AEG) is a transformative innovation in education, revolutionizing
the evaluation of written assignments for efficiency and consistency. This project delves into
AEG, harnessing natural language processing, machine learning, and deep learning techniques.
By utilizing a diverse array of features from the extensive Automated Student Assessment Prize
(ASAP) dataset publicly available on Kaggle, the study meticulously evaluates key algorithms,
including Support Vector Machine, Random Forest, and Long Short-Term Memory networks,
in automating essay grading. Notably, both the Random Forest and Long Short-Term Memory
(LSTM) algorithms stand out as front runners, demonstrating remarkable agreement with
human graders. They both achieved an impressive Quadratic Weighted Kappa score of 0.97,
echoing human-grade assessments, although there are distinctions in their MAE performance.

Furthermore, the investigation into grade normalization techniques uncovers their intricate
interplay with model performance and human grading standards. These discoveries offer
invaluable insights to educators and researchers, enabling them to refine automated grading
systems for enhanced consistency and reliability. This study not only advances the field by
shedding light on model selection and deep learning methodologies but also bridges the chasm
between theory and real-world application in educational assessment, making it a pivotal
contribution to the domain.

Overview
---------
This project aims to develop an automated essay grading system using natural language processing (NLP) and machine learning techniques. The system is designed to evaluate essays based on various criteria and provide a standardized score, making it valuable for educational institutions, online courses, and standardized testing organizations.

Code Description
-----------------
The AEG Project Code folder contains Python code for the AEG project that performs various text analysis and machine learning tasks. The code is organized into different sections, each serving a specific purpose.

Prerequisites
--------------
Before running this code, ensure that you have the following software and packages installed on your system:

- Python 3.x: The code is written in Python in a Jupyter Notebook, so you'll need Python installed.
- Python Libraries: Make sure you have the following Python libraries and packages installed. You can install them using `pip` if you haven't already:

    - numpy
    - pandas
    - scikit-learn
    - matplotlib
    - seaborn
    - nltk
    - gensim
    - tensorflow
    - keras
    - joblib

Code Organization
------------------
The code is organized as follows:

- [data_preprocessing.ipynb]: The Data Preprocessing Python notebook that executes the data loading, cleaning and preprocessing task of this project. It also performs initial feature extractions on the dataset and stores the features into a new csv file called "processed.csv" which is the input file for the second notebook.
- [model_training.ipynb]. The Model Training Python notebook that executes the development and evaluation of the machine learning models using the processed data from the "data_preprocessing.ipynb" file. It also performs some initial feature extractions before the model development. All models developed are saved into the Model Folder
- [Dataset/]: This folder is a zipped folder which contains the input data files used by the data_preprocessing.ipynb file.
- [processed.csv]: This is a CSV file that contains the processed data features from the data_preprocessing file and is used as the input data for the model_training.ipynb file.
- [Models/]: This folder is used to save trained machine learning models.

## Running the Code
To run the code, follow these steps:

1. Ensure you have Python 3.x installed.
2. Install the required Python libraries and packages listed in the "Prerequisites" section.
3. Navigate to the folder containing this README.txt file.
4. Execute the data_processing.ipynb and model_training.ipynb notebooks.

## Output
The code generates various outputs, including data visualizations and evaluation metrics. You can find the results in the outputs of each code block.

## Additional Information
For more details on how the code works and the specific tasks it performs, refer to the comments and documentation within the code files.

