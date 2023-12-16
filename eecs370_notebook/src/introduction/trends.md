# Trends

Computers are built via logic gates, which in turn are built on transistors. In this notebook, a transistor is considered as the fundamental unit of computers. The more transistors, the more amount of computation that can be done. But, the more transistors the more area/cost/power the processor will consume. 

Historically, we relied on electrical engineers to produce more advanced devices and transistors to 

If you want to learn more about how gates are built with transistors, I would recommend learning about logic design (EECS 270) or digital circuits (EECS 312). This will help build more of an intuition 


# Moore's Law and Dennard's Scaling

The main two trends within the computer architecture field involves the trend of transistors and their impact on microprocessors. These law goes as follows:

Moore's Law (Observation made by former Intel CEO Gordon Moore (1929 - 2023)):

```
The number of transistors on a microprocessor doubles every 2 years
```

Dennard's Scaling (Observation made by IBM Fellow Robert H. Dennard (1932 - Present)) :

```
As transistors get smaller, their power density stays constant, so that the power use stays in proportion with area.
```

These two observation together would indicate that every new generation of processors would have double the transistors, but still utilize the same amount of power. Since transistors are essentially a unit of computation, this would indicate that we would get a near 2x performance improvement every generation without sacrificing power.

However, Dennard's scaling broke in the mid-2000s. This indicated that while you could fit 2x the amount of transistors on your processor, you can't necessarily use them all at full power at the same time. If this were to be the case, then the processor would disappate enough heat to melt itself.

With the end of Dennard's scaling (and arguably the end of Moore's law depending on who you ask), engineers can't soley rely on device improvement to get the desired performance improvement. As a result, we must look at how the transistors are utilized to create better hardware depending on the use-case.


