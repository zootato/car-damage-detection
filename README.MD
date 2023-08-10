# Car Rental Image Damage Detection using VertexAI's LLM

![Car Image](car.png)

Welcome to the Car Rental Image Damage Detection project, where we leverage VertexAI's LLM (Language and Vision Model) capability to accurately determine if a car is damaged based on the image uploaded by the user. This solution eliminates the ambiguity around car damage assessment and provides insights into the type of damage present.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In the car rental industry, assessing whether a car has been damaged after the rental period is a crucial task. Traditionally, this process has been subjective, relying on manual inspections by staff. With the implementation of VertexAI's Language and Vision Model, we bring automation and objectivity to this process.

Our solution involves uploading an image of the car, and the system uses the LLM to analyze the image and respond with a determination of whether the car has sustained any damage. Additionally, if damage is detected, the LLM provides information about the type of damage present.

## Getting Started
To use the Car Rental Image Damage Detection system, follow these steps:

1. **Clone the Repository:** Begin by cloning this repository to your local machine.

    ```bash
    git clone https://github.com/zooxdata/car-damage-detection.git
    cd car-damage-detection
    ```

2. **Install Dependencies:** Install the required dependencies by running:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up VertexAI:** To use VertexAI's LLM, you will need change the variables - project_id, region

4. **Run the Application:** streamlit run app.py

## Usage
The Car Rental Image Damage Detection system is user-friendly and straightforward to use:

1. Upload an image of the car.
2. The LLM will process the image and provide feedback on whether damage is detected.
3. If damage is detected, the LLM will also provide information about the type of damage.

## Example
Here's a quick example of how the application works:

## Installation
If you'd like to set up this application on your own system, follow these installation steps:

1. Clone the repository as mentioned in [Getting Started](#getting-started).
2. Install the required dependencies using `pip` as mentioned in [Getting Started](#getting-started).
3. Configure the Variables (PROJECT_ID, REGION)
4. Run streamlit app.py

## Contributing
We welcome contributions from the community to enhance this Car Rental Image Damage Detection system. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or enhancement.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Create a pull request detailing your changes and improvements.

## License
This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute it as per the terms of the license.

---