# gymPlayground
Reinforcement Learning attempts and gimmicks using tensorflow, keras and gym environment

For example Cartpole: 

  - The goal is to make the agent balance the pole as long as possible (max. 500 steps). The actions are push the cart left or right.
     With a random action the visualization of the "game" looks like this:
    
      ![withutTraining](https://user-images.githubusercontent.com/71444220/96442958-31d6cb80-120c-11eb-8bab-5cccf7e6a5b5.gif)
    

     After 25 training iterations with 100 episodes each, where a 1-hidden layer Neural Network with 100 units was trained, using the relu activation function and Categorical Crossentropy as loss function to make the agent learn the best actions the visualization of the "game" looks like this:
     
     
  
