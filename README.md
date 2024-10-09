<h1>Cowrie: Creating a Honeypot</h1>

<h2>Description</h2>
This project focuses on setting up and configuring a Cowrie honeypot to simulate a vulnerable SSH and Telnet environment for monitoring unauthorized access attempts and capturing malicious activities. Cowrie provides a safe and controlled environment that logs all attacker interactions, including commands executed, files downloaded or uploaded, and other system activities. The data gathered will be used to analyze attacker techniques, study intrusion methods, and contribute to threat intelligence.

<h2>Goals</h2>


- <b>Deploy a Secure Honeypot Environment: </b>Install and configure Cowrie on a virtual machine to simulate an SSH/Telnet service that appears as a legitimate server to attackers.
- <b> Capture and Log Attacker Interactions:</b> Monitor and record all activities performed by potential intruders, including command execution, file transfers, and authentication attempts.
- <b>Analyze Collected Data:</b> Review and analyze the logs to identify patterns, common attack vectors, and any new techniques used by threat actors.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b>
- <b>Python</b>
- <b>Cowrie</b>

<h2>Environments Used </h2>

- <b>Kali linux</b>
- <b>UTM (virtual machine for macOS)</b>  

<h2>Walk-through:</h2>

Accessing Honeypot Configurations <br/>
<img src="https://imgur.com/n9EoSQl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SSH and Telnet Configurations <br/>
<img src="https://imgur.com/fasygX6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/k3kHYQ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Activating Honeypot <br/>
<img src="https://imgur.com/zRgjvvN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Monitoring Honeypot <br/>
<img src="https://imgur.com/M5xrLiL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/RY5gXpL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
</p>

<h2>Summary</h2>
The Cowrie honeypot project provides a practical approach to studying attacker behavior and learning how malicious actors interact with vulnerable systems. By simulating an SSH and Telnet environment, Cowrie allows the capture of information on each session, such as login attempts, executed commands, and file interactions.

The project begins with setting up a virtual machine to run Cowrie, configuring network settings, and tuning the Cowrie configuration for optimal performance and realism. The next step involves monitoring the honeypot for activity and ensuring all data is properly logged. Analyzing the logged data helps reveal attack trends and provides valuable information that can be used to protect actual production environments.
