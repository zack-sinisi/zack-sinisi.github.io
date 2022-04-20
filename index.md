## Portfolio

### Senior Game Developer at Black Zenith Entertainment. Working on Cyberpunk Samurai VR. January 2021 - Present
https://store.steampowered.com/app/1727900/Cyberpunk_Samurai_VR/

Cyberpunk Samurai VR is the first fully physics-driven, realtime VR PVP swordfighting game. It utilizes advanced techniques such as rollback, lag compensation, data compression, and client-side prediciton to provide a highly competitive and seamless swordfighting experience at a 120hz tick rate. I primarily worked on programming networked gameplay, ensuring that all gameplay is well synchronized even at a very high ping. I also theorized and programmed a system that allows intense and realistic sword clashes while mitigating the potential exploits inherent to multiplayer VR swordfightin. 
In addition to coding gameplay, I wrote shaders and created VFX effects to create elements such as plasma-sabers with heat distortion and procedural slash trails, and sparks that react to the direction and force of the hit. I also designed and developed a post-processing stack to tie together environments into a unified cyberpunk theme. 

### 3d Simulations Development Consultant. August 2020 - Present
I worked for a variety of companies to develop advanced 3D simulations. One example of a simulation that I designed and programmed was a medical simulation in which the client could perform a double bypass heart surgery. I researched how the surgery is done and created an accurate representation of it for the Oculus Quest. In my research, I watched videos of the surgery and consulted with doctors to learn more about the specifics of the surgery. Another example of a simulation that I helped develop was for an indie game in which a large number of complex enemies are present. The project had to be capable of running on very low-end hardware at a high frame rate, so I was brought in to optimize the simulation. I was able to increase the performance of the simulation by an order of magnitude by utilizing Unity's Job system and burst compiled code in a data-driven architecture.

![image](https://user-images.githubusercontent.com/104055906/164169867-1e0b32b7-b4e6-4aac-98da-f466f56d7e91.png)


#### Side Project - Utility-driven AI Simulation
For a personal upcoming game, I developed an almost-fully multithreaded, burst-compiled system for driving the action of AI using the Utility Theory. Each AI 'person' is given a set of personality stats. Each available 'action' in the world has a weight toward each stat, signifying its alignment towards the stat. Each AI chooses what action to take based on what action has the most utility, or value, to them which is determined by the stat weights of the action and the personality stats of the AI.
