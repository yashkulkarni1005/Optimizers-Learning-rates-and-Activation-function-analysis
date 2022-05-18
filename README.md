# Optimizers-Learning-rates-and-Activation-function-analysis
Analysis of performance of various optimizers like(SGD,Adagrad,Adadelta,RMSprop &amp; Adam ), various learning rates like(1,0.1,0.01,0.001,0.0001) and activation functions like(LeakyReLU , ELU , PReLU , sigmoid , tanh and relu) on mnist dataset.


•	Results:

1]Optimizer	|Train_Accuracy  |Validation_Accuracy :-

Adadelta  |0.7443     |  0.8488	 

Adagrad	  |0.8957	  | 0.9303	 

Adam	 | 0.9910	  |0.9879	 

RMSprop	  |0.9847	  |0.9862	 

SGD	     | 0.9463	  |0.9663	 




2] Effect of activation function on certain dataset:

Activation function	|Train_Accuracy	|Validation_Accuracy:-

LeakyRelu |	          0.9852	 |       0.9850	 

Elu	              |    0.9839	 |       0.9872	 

Prelu	           |   0.9912	 |       0.9890	 

Sigmoid	           |   0.8594	|        0.9356	 

Tanh	            |  0.9829	 |       0.9840	 

Relu	              0.9915	        0.9886	 

	

INFERENCE:-

•	In Optimizers, Adam optimizer performs the best.

•	In Learning rates, the optimal learning rate to be chosen is 0.001.

•	In Activation function, PReLU activation performs the best.

