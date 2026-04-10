<h1> Windows-Admin-Homelab </h1>
Repo that covers Windows OS installation, Active Directory installation, Organizational Units, User/Group Policy Management, File service sharing, Security Policy/Service Account implementation, Folder permission granting, & Access-Based enumeration.


 - <b2> Virtualization Software</b2>
    - VMware Workstation PRO 17

 
-  <b2>  Operating System(s)</b2>
    - Windows Server 2022 & Windows 11 client
    
    
    

<h2>Video Guides</h2>


Windows Active Directory Installation (VirtualBox/Server 2019/Windows 10)

[Windows Active Directory Installation (VMware/Server 2022/Windows 11)](https://youtu.be/g25kHfoG8hs)

- <b2> Installed Windows Server 2022</b2>
- <b2> Installed Active Directory, Remote Access, DNS Server, Group Policy MGMT, RAS & Remote Server Admin tools</b2>
- <b2> Promoted server to a Domain Controller; "SmithIT2022.local". </b2>
- <b2> Created Organizational Units: "West Palm Beach", "Fort Lauderdale", & "Miami" to simulate branch offices for SmithIT business </b2>
- <b2> Made categorized OUs within the branch office OUs to keep track of assets: "Computers", "Users", and "Servers". </b2>

 <p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/ee7edd3c4cd3ac4c2357b4558e56a7c67bbc0314/Win%20AD%20Serv%202022.png" alt="Sample Image"/>
  </p>



- <b2> Produced Security and Distribution groups for different departments</b2>
- <b2> Created Users and assigned them to their respective groups </b2>


 <p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/ee7edd3c4cd3ac4c2357b4558e56a7c67bbc0314/Win%20AD%20Serv%202022%202.png" alt="Sample Image"/>
  </p>

- <b2> Made and assigned Group Policy Objects (GPOs) to specific organizational units tailored to SmithIT business standards</b2>

 <p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/e58844e0f9daab3b18435a5d8d8f5ab4b5e7378c/Win%20AD%20Serv%202022%203.png" alt="Sample Image"/>
  </p>

  - <b2> Created a Windows 11 Client, joined it to the "SmithIT2022.local" domain, and verified client had full system functionality after being joined and updated.</b2>

 <p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/fc84b20ff8b0bfc09208a2c6d4c5dac278552e23/Win%20AD%20Serv%202022%205.png" alt="Sample Image"/>
  </p>

- <b2> Created a self titled folder, named "SHARED", that's connected to the server and mapped a network drive to it from my Windows Client </b2>

<p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/942525d70c9d842b29e916b27372e16df4543961/Win%20AD%20Serv%202022%204.png" alt="Sample Image"/>
  </p>

- <b2> Installed File Server Resource Manager (FSRM) to manage and classify sensitive data used within SmithIT.</b2>

<p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/c851ce927018b7dec158220dc883a4c6e26a8de0/Win%20AD%20Serv%202022%206.png" alt="Sample Image"/>
  </p>
  
- <b2> Produced a Quota Management template to automatically email the appropriate admins when the server's "SHARED" folder exceeds 70% of its storage capacity.</b2>

<p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/c851ce927018b7dec158220dc883a4c6e26a8de0/Win%20AD%20Serv%202022%207.png" alt="Sample Image"/>
  </p>

  - <b2> Made a File Screen Management template to restrict certain media types from being saved and/or shared by clients.</b2>

<p align="center">
    <img src="https://github.com/zay65/Windows-Admin-Homelab/blob/d8c48e1c28fdb2de0fdaaa28477e17109a6f4f46/Win%20AD%20Serv%202022%208.png" alt="Sample Image"/>
  </p>
