# Simulation-of-CAVs-and-Pedestrains

The file Video.mp4 shows us an example of VR simulation.

Process to run the virtual reality simulation:

Make sure that the Simulation computer (Simulink and Unity3D run in this computer) and Oculus Quest are under the same network.

Set the following IP:

Computer (server only): 192.168.0.101
  Oculus Quest(client): 192.168.0.104

MATLAB R2020b or higher.
Load Simulink Data (VRSimulationModelData) and Model (VRSimulationModel) in a matlab working space.


Operation order:

00. Install the .apk file (folder "Oculus Quest package") in Oculus
01. Make sure IP setting
02. lanch the unity server on computer ( CooperativeCrossingMultiLanes.exe in folder "Unity3D package"), click "server only"
03. lanch the installed .apk on Oculus
04. Set in simulink model, (pedestrian weight, CAVs initial position)
05. Start simulink model in real-time mode.

After that we can see the simulation in Oculus Quest. 
