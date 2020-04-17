# Tensorflow-Cat-Dog-Classification
A machine learning model to classify dogs and cats images using Tensorflow. 


Steps:
1. Use Keras's ImageDataGenerator to convert rgb images into array of number, specifiy batch size, specify class mode.

2. Preparing layers in CNN
3.train model
4. get accuracy 
5. test model

Batch size is 64 and run with 25 epochs.
The final validation accruacy reaches 0.76 and the final validation loss reaches 0.49.


*
One epocch: one forward pass and one backward pass of al the training examples
batch size: the number of training examples in one forward/backward pass.
steps per epoch: num_samples/batch_size



Great resources to learn CNN and its architecture in Kera:
1. https://machinelearningmastery.com/keras-functional-api-deep-learning/
2. https://keras.io/getting-started/sequential-model-guide/
3.https://towardsdatascience.com/convolutional-neural-networks-for-beginners-practical-guide-with-python-and-keras-dc688ea90dca
