![9LiX](https://user-images.githubusercontent.com/80645472/142637480-766417ad-597a-450a-b656-4405ddd78457.gif)

# smart elevator problem & solotuion

ELEVATORS PROBLEM AND SMART ALGORHITM-

in old elevators there is no algorhitm to direct the route of the elevator to the passengers calls it is working on some forms, to do it in an efficient way,
some soloution are trying to calibrate elevtors to smart by design an algorithm, this project build a smart algorhitm to elevator for an offline inputs to deacreae waiting time of elevators passengers.
to read more about the problem:

![XHXn](https://user-images.githubusercontent.com/80645472/142638164-5e56d2d2-e125-400c-abc6-d7053036dee6.gif)

# some Literature Review about smart elevators.
 First article-

this an article about the transition from old to smart elevators, moreover on the technology changes that allow and continue the progress of streamlining to waiting time of elevators passengers:  
https://www.popularmechanics.com/technology/infrastructure/a20986/the-hidden-
 /science-of-elevators
 
 Seconde article-

this article is about the same problem but with just one elevator in the building and how it works. 
https://elevation.fandom.com/wiki/Elevator_algorithm

 Third article-

an article that suggest a solotuion by  an mathematics-algorhitm by doing simple calculations and some condition to design a better algorithm for get the elevators to the destination by the "best" time. 
/https://austingwalters.com/everyday-algorithms-elevator-allocation

 Fourth article-

trying to solve the problem by finding the best position of the elveator beetween calls: 
https://idogreenberg.neocities.org/linked%20files/Articles/Elevators%20weighting%20time
%20optimization.pdf

 Fifth article-

an article that suggest to solve this problem by an AI algorithm that make decisions to stop by an database of the building that present the busiest hours and the common floor that are used, and by this information deceided where to go and stop. 
https://www.cs.huji.ac.il/~ai/projects/2014/The_intelevator/files/report.pdf


![Cwgf](https://user-images.githubusercontent.com/80645472/142638350-9f5199fb-5807-476f-ae79-34b066db7fdd.gif)

# Smart elevator algorithm:

We designed an online inputs algorithm in our first project ,to do that we get a call online an allocate the best elevator to embed this call to.
Now we have all the calls from the beginning , so we will allocate the best elevator and embed it to the calls before the elevator will start to run.
The algorithm will run over all the calls and for each call will check some conditions.
To start , we will check if there free elevators to get the call, from the free elevators we will calculate the time of the elevator to do this call and choose the elevator with the best time.
If there is no free elevator we will calculate the time of the elevators to done the last call and to do the current call and choose the elevator with the best time.
With those conditions and calculate we will allocate the best elevator to each call, we will use the inputs file to do it before running the elevator.

# UML for this project:




![Screenshot 2021-11-19 102247](https://user-images.githubusercontent.com/80645472/142592701-43d52ed5-7342-4f8b-aaf9-01bb4e8f5156.png)

