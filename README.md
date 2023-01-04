# SERS

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

 
 
 
 
 
 
 
 
 
 
 
 
 
 Silent Emergency Response System Web
Security and Ethics Paper 
Alex Caskey,
 Joey Fanara
Timothy Kerr, 
Zechariah Yue Zhu,
University of Missouri - Columbia IT4970 
Prof. Brian Mauer
November 2, 2021













When creating an app that deals with evidence, locating users, and handling life or death scenarios, one will likely run into security and ethical decisions. Team SERS does not take this lightly and has been brought up many times during the early stages of web application development. The primary purpose of the app is to help users through a highly stressful time of emergencies. The targeted end-users are the student body of Mizzou and the campus police department dispatch team. Being part of the potential user group, the developers must be thinking from the users' perspectives. Three things that come to mind when considering the ethics of our app are reliability, response time, and effectiveness. Additionally, security is also a significant part of the ethnic, so the team has taken several measures to ensure the security of the server and web application.
Addressing Ethical Concerns
The top priority of ensuring reliability is ensuring that no emergency request is unanswered, leaving someone in danger without help. This is essential because the Silent Emergency Response Team made a significant promise. During development, the effectiveness of the app is advertised to the audience of the engineering board. It's vital that we stay true to ourselves and avoid false claims, or else the Federal Trade Commission could seek action against us. (FTC, 2020) Since the app provides safety in emergencies, it is vital for us to prove that it can provide a service that gives the feeling of safety and provides a safe alternative in emergencies. This will be achievable in two ways, which is through testing and proving the app is needed. The testing part of our development process will be thoroughly through regression testing the application. The site should do what it's intended to in all circumstances one could potentially see in the field. The team can compare how much quicker the app could start resolving these emergencies compared to the emergency call line to prove the necessity. The goal is to have a safe yet effective way to reach victims who can't speak right away.

We have taken several steps to ensure the reliability of our web application that is reflected in our decision on the hosting server service, database, and APIs. We came across AWS because they have a reputation for being reliable using their five pillars of reliability. Amazon's five principles of reliability are the following: being able to recover from failure automatically, test recovery procedures, horizontal scalability, stop guessing capacity, and managing change in automation (2020, July 2). This reflects on the ethics of our users because their data shouldn't be slowed or lost in emergencies. Our app also needs to be trustworthy, which means we need to be honest with our data policies for our users. In our case of the web app, we can achieve this by prompting the dispatch user that no data created in the application can be deleted and that everything is archived for ongoing investigations. We will further enforce this by implementing strict file permission on the server. Every end-user should trust the application's functionality. Otherwise, they could be hesitant to use it in case of an emergency. We are still early in developing our application; however, our team has already achieved a significant piece in our reliability and trustworthiness. We did this by being able to use a google maps API for latitude and longitude lookups. This can help dispatch by getting a clear image of where they are and the surrounding areas. Our greatest challenge will have a database that fits our needs. The database will need to ensure that it is quick and responsive while also ensuring that it is secure with our end-users data. This will be achieved through the Firebase databases being hosted alongside our site. This will allow a more seamless transition of data and support the IOS side of the app. It's a top priority for our team to ease the process for the dispatchers, which is why we choose a robust database such as Firebase. We picked this database because of the simplicity of a NoSQL database. This will also allow us to have large amounts of data to sift through without the sacrifice of it being slow.

Given the nature of the application, a critical ethical component is our responsibility to minimize the end user's chance of missing an emergency. Our team will achieve this by creating a way to alert dispatch about an emergency happening on the SERS platform. This can be accomplished by having a unique sound for when a message comes in from a user to alert dispatch even if they are on another tab. Creating this sound will help the dispatcher's workflow while multitasking and ensuring that an emergency does not go unnoticed. This will further help our users experience the best chance of never missing an emergency as we know an application is only as good as it fits the end-users needs. In our context, this app is unethical if it doesn't help or fix the problem of helping victims in times of silence.

The other component of ensuring adequate response time is user-friendliness. One of our struggles so far has been with reaching out to campus PD. This is at no fault to anyone, but due to how busy MUPD is and it was logistically not possible to collaborate with them. We are doing this since we can't cater the app to the MUPD's dispatch system to improvise by keeping our app efficient and straightforward. To help us achieve this, we have been researching similar applications that have worked with a silent emergency dispatch system (Craft, 2003). This app is not intended to lure our users into watching ads and clicking on other sites for money. Our messaging app has a clear-cut end goal: to resolve emergencies of students like us as quickly as possible. We, as a team, are always trying to simplify an action through fewer clicks and more intuitiveness. So far, we have kept the dispatch side of things to two pages with an easy to adapt left to right workflow. Additionally, we are looking into the current workflow of how dispatch works and what we can do to make our site easy to transition to for the department.

We will also need to work on management and quality assurance. Going back to missing the luxuries of a natural development team, we will run into weird issues of us just being human and not automatically thinking the same thing at the same time. Even without a team manager, we have done to minimize this by creating a kanban board through Trello for our "sprints." This will help us be self-manageable and quickly check to see what everyone is doing. As far as the quality assurance role is, we all agreed on doing reviews for merge requests together. This is a two-for-one because we can also better explain what we are all doing and where we are coming from before going into the production phase of development (Code of Ethics).

Addressing Security Concerns
Another major factor we have taken into consideration is the security of our web application. The first step to ensure the security of our web application is to properly set up the server the application is going to be hosted on. The process begins by encrypting our Secure Shell (SSH) connection to the server itself. SSH is a protocol and software suite for sending data securely, tunneling applications, and administering distant computers (SSH,2021), much like our use case for our application host. Privileged users use SSH for secure interaction and remote access. Users include system administrators and application developers. Application security is rooted in the host of the service provider itself. We utilized an SSH key, a secure access credential, using critical key pairs based on public key infrastructure technology and encryption to provide secured authentication. Not only does SSH keys make the server more resilient to dictionary attack or brute-force attack, but they also simplify the login process for users so that users do not have to remember the long password each time. 
 
Every SSH key pair contains a public key and a private key. The two most common mathematical techniques used to produce SSH keys are Rivest–Shamir–Adleman (RSA) and Elliptic Curve Digital Signature Algorithm. These algorithms would produce a lengthy combination of numbers and letters to form a passphrase prone to brute force attack. The public key is stored on the server to encrypt data that the user can only access with the corresponding private key. On the Ubuntu server, all trusted and authorized public keys are stored at /home/b/. ssh/id_rsa.pub. On the other hand, users would possess a private key that verifies the user's identification and authentication to access the server. For instance, we generated a private key named SERS2.pem, and that is shared amongst team members. When we make a connection request to the server using SSH, the server will verify the private key with the public key to determine the users' identification. However, despite using SSH key pair effectively preventing brute force attacks from gaining access to our server, there are security risks. The private keys stored on the users' local machines may be vulnerable to social engineering attacks. We have decided to use the Google Cloud Key Management service that protects our private keys to provide additional security. Given the nature of the data stored on our server, it is essential to manage SSH keys regularly and limit each user's access to the server to prevent malicious access to the server and its data.
 
The server was initially set up with a limited number of users, and each user could quickly gain root privilege and full access to the database and the application. Thus, it is crucial to set up limited access to user accounts. In addition to the original users generated with the server, we have created multiple roles such as developer, admins, and dispatch. Each user would have limited access to the server and its data. We utilized the principle of least privilege, which states that each user or program should have only the bare minimum privilege to perform its function (Schneider, 2003). A dispatch user would only be able to read, access but not write the data, whereas the admin could have the privilege to modify data if necessary. The same principle applies to the web application when designing the database to prevent unauthorized access.
Additionally, root login through SSH is disabled to prevent malicious access to the entire system. This can be achieved by modifying the /etc/ssh/sshd_config file and changing the status of PermitRootLogin to no. Most importantly, Fail2Ban is initialized on the server. Fail2Ban is a powerful tool to prevent brute force attacks by banning connections if more than three failed connection attempts are found from the same IP address. Once the production of the web application is completed and put into use, the admin SSH login will be limited to the dispatch office's IP address only, and any other unauthorized attempt will be banned.

 In addition to the limited access on the users, limited access to the documents is implemented. All files on the server have permission assigned to users, groups, and others. It is unwise to have all files or folders have 777 permission, enabling all users to read, write, and execute files. Instead, files that can be publically accessible should have 644 permission, which makes them unable to be executed by anyone, modifiable by owner only, and accessible to users. This will prevent any data modification that could lead to security issues.
 
While several measures have taken place to ensure the server's security, many more are to be implemented to protect data transmission on the Web application. When designing the system, one fundamental practice is always to use the POST method instead of the GET method when transmitting sensitive data. The latter does not cache or remain in the browser history. 

On top of that, we implemented the Secure Sockets Layer (SSL) certificate to transfer sensitive data such as login and geo-location data. SSL would generate session keys that encrypt and decrypt all communications. It would also generate a message authentication code in the transmission to prevent any message alteration and confirm the identity of both the server and users. Another benefit of having an SSL certificate is that it would display the security padlock on the browser, increasing the website's credibility and making the users feel more comfortable sharing information (Nikolov,2018).SSL stands for Secure Sockets Layer, and it is more commonly referred to as Transport Layer Security (TLS). It is used to ensure that any data sent between users and websites remain unreadable. It scrambles data in transit using encryption methods, preventing hackers from accessing it as it travels over the network(Adeenze-Kangah,2019). Once the SSL certificate is implemented, we could initiate the Hypertext Transfer Protocol Secure (HTTPS) redirect instead of Hypertext Transfer Protocol (HTTP). The added security for HTTPS is reflected in its protection and encryption of communication. Furthermore, HTTPS will ensure the web owner can be verified and can be trusted. On the other hand, HTTP is often marked by browsers as not secured or unsafe, which would seem untrustworthy by the end-users.
 
While HTTPS protects the user while exchanging data and prevents malicious website usage with an SSL certificate, additional security is needed for better server protection. Another form of offensive attack commonly found to slow or even halt network traffic to and from the server is called Distributed Denial-of-Service (DDoS) attack. To protect against this category of attack, we have linked Cloudflare to our website. Cloudflare utilizes the edge network to provide a faster and safer connection to the web. Edge networks function by becoming the intermediary step in between servers and clients receiving data from the servers. It operates by moving the computational function away from the data center(which hosts hundreds of IoT devices, slowing speeds and taking up network resources) and relocates it near the edge of the network, closer to the end-user. Edge networks also protect against DDoS attacks that aim to interrupt network traffic by acting as a sacrificial barrier between the outside internet and our website. Additionally, To further secure the database, we intend to host the server and the database on Firebase, which provides many security measures.

Nevertheless, there are several limitations with those security practices, such as TLS connection and database security. Although TLS uses a combination of asymmetric and symmetric cryptography to provide confidentiality and non-repudiation, it also has a longer latency than most other secure encryption technologies. When TLS is implemented, the site's traffic will experience increased latency(Calzavara,2017). The difference in loading speed is tangible right now during the production mode as there is very little traffic. Still, this issue must be addressed eventually when a high volume of traffic contacts the police dispatch every day. Additionally, SSL has some vulnerabilities that could be exploited on the web application. The POODLE vulnerability, for example, makes use of SSL 3.0's proclivity to ignore padding bytes when in cipher block chaining mode(CISA,2014). Yet, the benefits of having SSL outweigh the disadvantages. The users will be reassured when they see the green padlock in the URL bar and more willing to use the service.

Database security is also our top priority. Our initial plan was to set up the Neo4j on a different server to prevent compromises. However, after research, we have decided to switch to firebase hosting and employed a firestore database to take advantage of the security features provided. Firebase utilizes real-time listeners to keep data in sync across the web and IOS app. It enables the user to save data locally and sync it with the database once connectivity is restored. Firebase provides a client-SDK that handles networking and authentication and provides backend security controls that handle advanced data validation logic while allowing easy data access (Moroney,2017).

Ethics and security are the top priority in development. We have taken several precautions to ensure the reliability, effectiveness, and response time to address the ethical concerns. We have also employed HTTPS redirect, TLS / SSL certificate, SSH, user access control, and firebase database to address the security concerns. 


References

 
A. W. S. (2020, July 2). Reliability - AWS Well-Architected Framework. Amazon. Retrieved October 14, from https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.reliability.en.html

Adeenze-Kangah, J., &amp; Chen, Y. (2019). Detecting proper SSL/TLS implementation with usage patterns. Journal of Physics: Conference Series, 1176, 022045. https://doi.org/10.1088/1742-6596/1176/2/022045 

Bhasin, S. (2003). Web Security Basics. Muska & Lipman/Premier-Trade.

Bhadoria, I., Patel, P., &amp; Fiaidhi, J. (2020). Chatapp with encryption using Firebase. https://doi.org/10.36227/techrxiv.12116565 
 
Calzavara, S., Focardi, R., Squarcina, M., & Tempesta, M. (2017). Surviving the web: A journey into web session security. ACM Computing Surveys, 50(1), 1–34.

CISA, C. I. S. A. (2014, October 17). SSL 3.0 Protocol Vulnerability and POODLE Attack | CISA. Cybersecurity & Infrastructure Security Agency. https://us-cert.cisa.gov/ncas/alerts/TA14-290A
           
Craft, J. R. (2003). Portable document format (PDF): Standardizing document files for publication. DESIDOC Bulletin of Information Technology, 23(1), 19–24. https://bja.ojp.gov/sites/g/files/xyckuh186/files/media/document/leitsc_law_enforcement_cad_systems.pdf

FTC, F. T. C. (2020b, July 24). Marketing Your Mobile App: Get It Right from the Start. Federal Trade Commission. https://www.ftc.gov/tips-advice/business-center/guidance/marketing-your-mobile-app-get-it-right-start

Google. (2019, March 14). 7 tips on Firebase security rules and the Admin SDK. The Firebase Blog. https://firebase.googleblog.com/2019/03/firebase-security-rules-admin-sdk-tips.html
           
IEEE Computer Society. (n.d.). Code of Ethics. https://www.computer.org/education/code-of-ethics
 
Josh Pauli. (2013). The Basics of Web Hacking : Tools and Techniques to Attack the Web. Syngress.
 
Linode. (2021, August 20). How to Secure Your Server. Linode Guides & Tutorials. https://www.linode.com/docs/guides/securing-your-server/
 
Nikolov, I. (2018, May 18). Why An SSL Certificate Is Important For Your Company Website. Forbes. https://www.forbes.com/sites/forbestechcouncil/2018/05/18/why-an-ssl-certificate-is-important-for-your-company-website/?sh=4c4f90dd1dc3

Moroney, L. (2017). Using firebase hosting. The Definitive Guide to Firebase, 93–106. https://doi.org/10.1007/978-1-4842-2943-9_5  
​​
Public Key authentication - security, automatic log-in, no passwords. (n.d.). SSH.Com. Retrieved October 14, 2021, from https://www.ssh.com/academy/ssh/public-key-authentication
 
Saran, C. (2019). Layer Your Approach to Web Security. Computer Weekly, 16–20.

Schneider, F. (2003). Least privilege and more [computer security]. IEEE Security & Privacy, 1(5), 55–59. https://doi.org/10.1109/msecp.2003.1236236

What is a distributed denial-of-service (ddos) attack ... (n.d.). Retrieved November 2, 2021, from https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/. 

 
 



