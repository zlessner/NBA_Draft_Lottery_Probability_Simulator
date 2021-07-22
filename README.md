# NBA Draft Lottery Probability Simulator

## Instruction

This Jupyter Notebook produces draft lottery odds for the NBA's current format and also for a format from the following suggested rule changes:

- The top five picks get determined by the lottery instead of the top four
- The bottom 16 teams enter the lottery instead of the bottom 14
- The 1000 lottery balls are redistributed as shown in the following table:


<p align="center"> 
<img src="https://github.com/zlessner/NBA_Draft_Lottery_Probability_Simulator/blob/master/lotteryOdds.png">
</p>



## Solving Method

I initially used recursion to determine each team's probability for the picks determined by the lottery.

I then decided to simulate the draft millions of times with the current and hypothetical odds so that there would be a big enough sample to converge on each team's probabilities for the entire lottery.

The result for the hypothetical odds is shown in the csv file. 