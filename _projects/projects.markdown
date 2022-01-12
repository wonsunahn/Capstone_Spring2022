---
layout: page
permalink: /projects/
---

# Capstone Project List - WORK IN PROGRESS

<!--SO FAR: 4+6+3+3+ 3+3+3+2+2+2+4+?-->



Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (27 January) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (29 January). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - [Develop a kernel extension for an Open Source File System]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Fall-2021.pdf)
 

**_Project Background_**
Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project.  Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.
Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years.  Because of the proprietary nature of the file system we will be using an open source equivalent for this project.   Working in the C language, students will gain real-life experience developing for embedded, distributed systems.
Project Summary 
In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.
Project Details 
 Over the course of this Capstone project, students will accomplish the following high-level goals: 
•	Download and install FUSE on Linux.
•	Work through a NetApp provided initial custom example to understand the basic architecture.
•	Create a read/write file system as an underlying test bed and explore the properties of this system.
•	Write the kernel extension (using the C programming language) to implement a user space reporting function.
•	Execute automated tests during the writing of the kernel extension.  Enhance the automated tests as necessary.
•	Enhance the file system to store user space consumed data in an in-memory database.
•	Update the in-memory database based on incoming fileops.
•	Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.

	 
 
 
**_About NetApp_**   
NetApp is the Data Authority in the Hybrid Cloud.
Throughout the world, leading organizations count on NetApp for software, systems, and services to manage and store their data. We help enterprises and service providers envision, deploy, and evolve their IT environments. Customers also benefit from our open collaboration with other technology leaders to create the specific solutions they need.  
Our team is passionate about customer success. Our company culture and work environment support that dedication. Together with our global network of partners, we are united in one goal: to help our customers achieve the outcomes that matter most to them. To learn more, visit www.netapp.com. 
The project is driven by the Scale Out Storage team which provides the file system infrastructure within the kernel to achieve high performing, scalable containers that are a key component of the NetApp Data Fabric architecture.
NetApp At-A-Glance 
•	$6.0B+ in revenue 
•	Over 10,000 employees in more than 150 offices worldwide 
•	Great Place to Work Institute's "World’s Best Multinational Workplaces" list 
•	Great Place to Work Institute’s “Best Companies to Work for in APAC” list 
•	Great Place to Work Institute’s “Best Companies to Work for in Europe” list 
•	FORTUNE Magazine's "100 Best Companies" list 
•	A FORTUNE 500® Company 
•	Member of S&P 500 and NASDAQ 
•	Stock symbol: NTAP 
•	Close partnerships with global industry leaders.



### CGI - [Client Onboarding]({{site.baseurl}}/projects/pdfs/CGI.pdf)

**Check PDF** 

**Project Overview**
To enhance and improve a client-onboarding portal that serves as an Onboarding and Knowledge Management solution, designed to make the process of onboarding new CGI members to project teams more efficient and effective. Students will work with a team of CGI experts to not only help solve this problem/challenge but also learn critical skills needed as they enter the workforce.

**Project Details**

The proposed Onboarding and Knowledge Management portal will achieve a couple of objectives:
* Support a structured way for new team members to be onboarded to a project/team
* Simplify the portability of the building and deployment of the application.
* Automate workflows where project knowledge can be captured, shared, and archived on an ongoing basis

The following non-exhaustive scenarios have been identified to achieve these objectives:
* The ability to build and copy templates of onboarding tasks
* Add ability to associate onboarding projects to client(s)
* Improve the application portability by dockerizing the application
* Improve the code quality using static code analysis from SonarQube

The outcome of this Capstone Project would be a software solution that meets these objectives, along with its associated artifacts like architecture documentation, user personas, user journeys/workflows, UI/UX prototypes, software development environment setup, code documentation, testing artifacts, etc.

Students should expect to learn about modern software-development techniques in an enterprise setting such as:
* Design-thinking methodologies
* Ideation and UI/UX rapid prototyping
* Agile software development
* Product and Project management
* State-of-art technologies

Students are expected to know or easily learn the following technologies:
* Angular (TypeScript, HTML/CSS)
* Spring Boot (Java)
* Jsoup
* Sonarcube
* Docker
* Git
* MySQL
* IntelliJ/VS Code
* Trello


* Team Size: 5/6 students
* POC: Anthony DeLuca (anthony.deluca@cgi.com)


**Note: NDA and/or IP agreement will need to be signed for this project.**

### GreenSpace - together with IS more requirements needed

**_About GreenSpace_**

GreenSpace was conceived out of real-world frustrations with current software that is utilized in the green industry today. Because of that experience, we set forth to deliver a simple, intuitive, cost effective landscape platform that allows all sizes, types and parts of the organization to maximize value delivery.

Our mission is to provide that do-everything-owner with the ability to provide autonomy to their employees knowing that there is a system in place that eliminates all the minutia of the day-to-day activities required to run the business. We want to let these organizations focus on their customers and the landscaping again; bringing back the nostalgia of having that pick-up truck, mower and the passion that they felt for this career in the first place.


**_About the Project_**

We would like to develop an intuitive-to-use application that allows landscaping companies (crew members, managers, administrators, etc) to perform time tracking, generate reports, allow manual scheduling, etc. As of now, the users of this application will be the landscaping companies.

Features overview:  
- Time Tracking 
- Job Costing 
- Scheduling
- User Dashboard (if time permits)


**_Initial System Requirements/Features_**

[Current epics and features can be found here.](https://docs.google.com/document/d/1Rx-fiFhNaq1wS588-SJSk8nOJDwpGBcHehGBoRAcqyE/edit#)

**_Interested in working on this project?_**

This is a joint project between CS and DINS. That means that it is open for students from both departments to work on. Exciting, right?

Here, what you should keep in mind if you are interested in working on this project:
The development team (student) will use their program/method of choice to keep track of who is working on which epic and/or feature.
Weekly client meetings: Students must find a weekly client meeting time that works for EVERYONE in the team.  If that is not possible, the weekly client meeting time becomes Tuesdays 4:00 pm - 5:00 pm EST (in room 411 IS Building - or through Zoom).
Tools: The team must propose the frameworks/tools they will use in this project as part of the project proposal.
Hosting: Pitt may be providing hosting capabilities via Azure if possible. However, GreenSpace can provide access to an AWS machine/environment for development if Azure is not available.
CS 1980 students must be available to meet Tu/Th 4:00 - 5:15 (room 411 IS) throughout the whole Fall 2021 semester
The CS midterm presentation is optional for IS students
There will be a maximum of 6 team members in this project

Still have questions?  Feel free to contact your class instructor.

**Note: NDA and/or IP agreement will need to be signed for this project.**

* Team Size: 3 students
* POC: Chip Loving


### Visimo

Our client runs a fertility consulting clinic and wishes to develop a web app for her clients to use that will improve both the clients’ experience and the effectiveness of the clinician. The app will survey the clients’ daily habits using a series of checklists, which will be customizable depending on the individual client’s needs. (For example, there may be a “base” survey that all clients take, and then an additional “diabetics” survey that clients with diabetes will take, and so on.) The app will then make recommendations about what habits need to change in order to optimize fertility, and will offer coaching, a place to record notes, and a dashboard for viewing metrics and analyzing progress.

There will also be convenience features, such as the ability to scan barcodes on food products and automatically record and track the clients’ eating habits and nutrition, and ideally the ability to integrate with Health app in iOS, and track things like exercise, meditation and sleep.

This will be a designed and built as a “progressive web app,” which is a cutting-edge class of web applications that is able to perform much of the functionality of a native mobile app, while still running through the browser as a traditional web app would and not requiring any sort of downloading or installation from an app store.  

The actual process will involve:

    - Wireframing the app with the client
    - Designing and optimizing the UI and UX of the app
    - A data modeling and software design/architecting phase
    - The establishment of a project plan, with individual responsibilities, timelines and milestones
    - Implementation and deployment

As for the last point, we follow a CI/CD approach in our software projects, so that students will be exposed to this software development best practice, and learn how to work on a team that adheres to it. We will deliver a stripped-down, minimally viable product (MVP) very early in the process, so that the client can begin receiving value from our work as soon as possible, and then we will iterate from there, with frequent releases that each offer small upgrades in features and performance.

The final product will be hosted by VISIMO and deployed on a Kubernetes cluster in our Azure cloud environment. As a result, students will also have a chance to learn about containerization using Docker, container orchestration via Kubernetes, and the overall process of deploying and maintaining a cloud-based web app.

* Team Size: 3/4 students
* POC: TBD



## CS Faculty Projects


### RISC-V web based simulator for CS447

For DECADES CS 447 was taught using MIPS assembly language. However, MIPS processors are not that common anymore (RIP PS and PS2) (they still live in network equipment though :).
On the other hand, the RISC-V architecture (open-source) is gaining some momentum, and you can even buy some boards to have fun with it.

We are still using MARS (which we all hate ;), but we want to push the development of an alternative that uses RISC-V. wilkie developed a web-based alternative, but it's still not ready for primetime: https://gitlab.com/wilkie/rawrs
This tool is called RAWRS (RISC-V Assembler and Workable, Rewritable System) - it's an acronym it can mean whatever we want! - and it's a web-based tools (bye bye Java).

The objective for this project is to develop this tool further to a point where it can be used for CS 447.
- This includes making improvements to the CPU simulator we use (C development) to let students know when they don't follow conventions.
- Adapt the website (Javascript development) to new functionality.
- Fix any outstanding/detected bugs in the software.

The tool is written in (modern) Javascript where we predict most of the development will be focused. But you will also have the opportunity to stretch your assembly muscles. As the RISC-V simulator is backed by a RISC-V kernel :D

* Team Size: 3 students
* POC: David Wilkinson (wilkie) and Luis Oliveira (loliveira@pitt.edu)




### GUI for AppArmor

Bill Garrison and Jack Ullery (a fellow student) have been working on a project this summer in which they are laying the foundation for a graphical interface for AppArmor, a Linux kernel extension that can enforce per-process access controls. AppArmor allows users to restrict apps from accessing resources they shouldn't need, and can be used to sandbox applications from one another as much as possible (with allow lists for the resources that are necessary). A graphical interface for this tool could behave somewhat like a modern firewall, allowing users to configure what's allowed vs. blocked after reviewing historical accesses.
You will be collaborating closely with Jack which will guide the team with the knowledge he's already gained about how AppArmor works and how one configures it.
This is a systems project (so it would be ideal to have completer CS1550!).
Team size: 4–5 students
POC: Bill Garrison (bill@cs.pitt.edu)



### Pedestrian smart maps



* Team Size: ? students
* POC: Panos, Konstantinos, Aurora


### Activity Recognition Data Collection Smartphone Application

Machine learning models are commonly used to perform activity recognition from sensing data collected using smartphones.
Typically, data is shared to the cloud, where the final model is trained.
Recently, there has been a trend to train personalized models on smartphones without the need for sharing the data.  
In this project, students will develop and enhance an activity recognition app on Android OS. Students will carry out the following tasks for this project.
Download and install an activity recognition app
Reproduce the results for training personalized activity model
Enhance the app to enable labeling and logging of sensor data
Implement extensions to visualize the data
Write and execute test case to test the system

* Team size: 2-3 students
* POC: Stephen Lee

### Web-based Image and Point cloud Annotation Tool
Data annotation software is important for many computer vision projects.
The goal of the project is to design a web-based 3D annotation tool. Students will design a web interface to visualize point cloud data.
In addition, the tool will allow users to select, define and describe regions of the data.
The software should also support loading and saving of annotations. Students should be familiar with HTML and javascript to carry out this project.

* Team size: 2 students
* POC: Stephen Lee


### Studying Scheduling Behavior on Heterogeneous Memories

Areas of Interest: Operating Systems, Computer Architecture
Necessary/Required Skills: Knowledge of Linux and Python / Shell Script
Desired Skills: C Language

Heterogeneous memory systems have been recently adopted by hardware vendors to balance high capacity (provided by PMEM--persistent memory) and performance (offered by DRAM). Using recent OS support, as in Linux kernel 5.1+, the different types of memory (e.g., high-density/slow PMEM vs low-density/fast DRAM) can be seamlessly accessible by the CPU. A key challenge is to automatically allocate the application data to the most suitable type of memory. In this project, we will experimentally experiment with a newly released kernel patch (autonuma, see https://lwn.net/Articles/845102/). For this, we want to measure/instrument/inspect (using existing Linux kernel infrastructure) the decisions made by the data placement scheme (autonuma) in order to better understand their decisions.

We envision the following (tentative) tasks for the project, with deadlines every 2 weeks, approximately:


- Install specific patch on Linux in Chameleon Cloud (Already done, but it would be nice to learn!)
- Emulate a Persistent Memory on a Chameleon Linux machine (See https://software.intel.com/content/www/us/en/develop/articles/how-to-emulate-persistent-memory-on-an-intel-architecture-server.html)
- Create scripts or C code that will track online memory page migration and object allocations (e.g., https://linux.die.net/man/5/numa_maps)
- Your software will identify which pages (objects) were migrated and identify which objects remained in their source allocations
- Lastly, you will (hopefully automatically) generate and analyze data/plots summarizing the decisions made by autonuma for an application's allocations

* Group Size: 1-2 students
* POC: Diego Braga (dmoura@pitt.edu), Daniel Mossé (mosse@pitt.edu), Vinicius Petrucci (vpetrucci@pitt.edu)


### Optimizing Web Browsing Energy Efficiency

Areas of Interest: Operating Systems, Computer Architecture
Important Skills: Knowledge of Linux, System Programming (C/C++), Python

An ever-growing amount of mobile devices trying to stretch their battery life, in conjunction with increasingly complex web pages, create a delicate balancing act between energy efficiency and performance. Existing OS-based power management techniques designed to tackle this issue rely on generic system-level metrics that are unable to anticipate the complex behavior of a web browser, which can lead to energy inefficiency or poor user experience during web browsing activities.

In this project, we propose a new power management approach that leverages application-level information to identify major phases in the web browser (Chromium in our study). We will monitor the behavior of the application at a finer granularity (compared to OS schemes). Based on runtime observations, we will modify the web browser's behavior to evaluate the effect of different hardware mappings (CPU type and speed) on performance/energy usage. Ultimately, we seek to design a better method of mapping application phases to appropriate hardware usage patterns. This is an ongoing project initiated by prior students and new students will be able to leverage and extend experimental infrastructures.

We envision the following (tentative) tasks for the project, with deadlines every 2-3 weeks, approximately:

- Instantiate the experimental platform on another set of machines
- Extend and scale our Python script environment to match the resource capabilities of those new machines
- Provide the adequate extended monitoring capability and configuration knobs to a Machine Learning scheme (another student working on this part) that will leverage such a new exposed environment
- Run experiments and collect performance/power data for plotting, analysis, etc

* Group Size: 1-2 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)

### Web Apps to Support Community Enablement

This team (3-4 CS students) will join the Digital Ambassadors project, a collaboration between SCI and the Hill District’s citizens and businesses.  The project’s overarching goal is to provide Hill District high school youth with opportunities to learn and apply digital skills. A hallmark of the program is these youth working as technology-focused interns in local businesses. This CS team will direct engage with the youth and businesses to provide technology know-how and horsepower to develop a new business or social engagement technology that can be used by these businesses and supported by the youth interns.  This team will lead the development of a mobile application or mobile-friendly reactive web application.  The team will engage with stakeholders to elicit functional requirements, present designs and prototypes for feedback, and deliver a working solution by the end of term.  This project provides unique experiences for a CS student to leverage their technical skills to address the Digital Divide in the Pittsburgh community.  The project will be supervised and support by Prof Biehl and Prof Farzan.

* Group size: 3-4 students
* POC: Jacob Biehl and Rosta Farzan ({biehl, rfarzan}@pitt.edu)

### TBD

* Group size: ? students
* POC: Malihe Alikhani and Dmitriy Babichenko
