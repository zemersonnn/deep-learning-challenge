# deep-learning-challenge
Challenge 21 for Bootcamp 

* Overview of the analysis: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using knowledge of machine learning and neural networks, the features in the provided dataset create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

* Data Preprocessing
* What variable(s) are the target(s) for your model? Application type, classification (government organization classification), and was the money used effectively. 
* What variable(s) are the features for your model? "IS_SUCCESSFUL", "CLASSIFICATON", "APPLICATION_TYPE"
* What variable(s) should be removed from the input data because they are neither targets nor features? EIN and NAME columns can be dropped. 

* Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why? Neurons used; 80, 30, 1. The model consisted of two hidden layers and one output layer. 
* Were you able to achieve the target model performance? There was an accuracy of 73%. This is slightly below the target model performance. 
* What steps did you take in your attempts to increase model performance? Adding neurons and layers to impact the models performance. 

* Summary: The accuracy is at 73% and loss of 56% with the trained model used. The epoch value is set at 200 and takes approximently 8 minutes and 35 seconds to run. The value 200 was chosen so there are enough complete passes through the entire training dataset through the neural networks learning algorithm. 
