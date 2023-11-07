![1.png](doc/1.png)

Digits is an application that allows users to:<br>
* Register an account.<br>
* Create and manage a set of contacts.<br>
* Add a set of timestamped notes regarding their interactions with each contact.<br>

**Installation**<br>
First, install Meteor.

Second, **download a copy of Digits**. Note that Digits is a private repo and so you will need to request permission from the author to gain access to the repo.<br>

Third, cd into the app directory install the required libraries with:<br>

**meteor npm install**<br>

Once the libraries are installed, you can run the application by invoking:<br>

**meteor npm run start**<br>

When you run the app, Here is the output:<br>
![img_2.png](doc/img_2.png)
If all goes well, the template application will appear at http://localhost:3000.<br>

Lastly, you can run ESLint over the code in the imports/ directory with:<br>
**meteor npm run lint**<br>


## User Interface Walkthrough
**Landing Page**<br>
When you first bring up the application, you will see the landing page that provides a brief introduction to the capabilities of Digits:

![1.png](doc/1.png)

**Register**
If you do not yet have an account on the system, you can register by clicking on “Login”, then “Sign Up”:<br>
![2.png](doc/2.png)


**Sign in**<br>
Click on the Login link, then click on the Signin link to bring up the Sign In page which allows you to login:
![3.png](doc/3.png)

**User home page**<br>
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to list contact and add new contacts:<br>
![5.png](doc/5.png)

**List Contacts**
Clicking on the List Contacts link brings up a page that lists all of the contacts associated with the logged in user:<br>
![6.png](doc/6.png)

This page also allows the user to add timestamped “notes” detailing interactions they’ve had with the Contact. For example:<br>
![7.png](doc/7.png)

**Edit Contacts**
From the List Contacts page, the user can click the “Edit” link associated with any Contact to bring up a page that allows that Contact information to be edited:<br>
![8.png](doc/8.png)

**Admin mode**
It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they get access to a special NavBar link that retrieves a page listing all Contacts associated with all users:<br>
![9.png](doc/9.png)