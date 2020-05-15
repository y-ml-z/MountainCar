# MountainCar

## RLGlue.py, mountaincar_env and agent.py from OpenAI: necessary "default notebooks" for this project
The project is for an under powered car to make it to the top of the hill:
![](https://camo.githubusercontent.com/c346664b8e3c0b4839656b84620f59676e783bd1/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f312f31382f4d6361722e706e67)


The car is under-powered so the agent needs to learn to rock back and forth to get enough momentum to reach the goal. At each time step the agent receives from the environment its current velocity  and it's current position . Because our state is continuous there are a potentially infinite number of states that our agent could be in.

## Tile Coding Function

![](https://miro.medium.com/max/3602/1*AZXJ9lWBReLEcEQDt0_jpQ.jpeg)

More information: https://www.cs.utexas.edu/~pstone/Papers/bib2html-links/whitesontr07.pdf

In this project:

Using function approximation in the control setting
Implement the Sarsa algorithm using tile coding
Compare three settings for tile coding to see their effect on the agent
