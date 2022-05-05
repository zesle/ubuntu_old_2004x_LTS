Installation Guide
==================

It's really easy to install ZesleCP control panel and it only takes up to 8-10 minutes.

Our support team is available, feel free to contact us [here](https://zeslecp.com/contact) or email us at [zeslecp@gmail.com](mailto:zeslecp@gmail.com).

**Server Requirements:**

*   Ubuntu 20.04 Server or CentOS 7/8 Server
*   Minimum 2 GB RAM
*   10+ GB hard-drive recommended
*   `root` SSH access to your server

### Steps

1.  **Connect to SSH Terminal —** Open any SSH terminal (ex: [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)), connect to your Ubuntu/CentOS server and login as a `root` user.

2.  **Run install command —** Copy-paste the following command into SSH terminal and hit Enter key.

    **Compatible with Ubuntu 20.04 and CentOS 7/8:**  
    `cd /home && sudo curl -o latest -L http://release.zeslecp.com/latest && sudo sh latest`

    Hit enter after pasting the installation command. Once the installation is started, wait for the 8-10 minutes for the installation to complete.

    ![ZesleCP Installation Start](https://zeslecp.com/images/docs/v3/install/zeslecp-install-command.png)



3.  **Installation Completed —** You will see all the details in the terminal after the installation has finished. See the example screenshot below.

    ![ZesleCP Installation Finished](https://zeslecp.com/images/docs/v3/install/zeslecp-install-finished.png)



4.  **Open the control panel —** Open control panel link, as mentioned in your terminal at point 2., in your browser. Ex: `https://YOUR-SERVER-IP:2087`

    This might show you the "Site is not secure" or "Potential risk" warning. You can safely ignore it because there is nothing to worry about. See the example screenshots of different browser windows below:

    ##### [Chrome Browser Warning Message](#)

    ![ZesleCP control panel](https://zeslecp.com/images/docs/v3/install/warning-chrome.png)

    ##### [Firefox Browser Warning Message](#)

    ![ZesleCP control panel](https://zeslecp.com/images/docs/v3/install/warning-firefox.png)

    ##### [Internet Explorer (IE/Edge) Browser Warning Message](#)

    ![ZesleCP control panel](https://zeslecp.com/images/docs/v3/install/warning-ie.png)



5.  **Login —** You should see ZesleCP login screen now. Username `root` and password (received from the installation process in command-line terminal).

    ![ZesleCP login page](https://zeslecp.com/images/docs/v3/install/zeslecp-login.png)



6.  **Licence -** After login, you need to get your licence. Get one from [here](https://zeslecp.com/pricing).

7.  **Custom Nameservers -** Optionally, you can configure your own [custom nameservers](https://zeslecp.com/docs/server-configuration/setup-custom-nameservers).

8.  **Create Your First User Account** _(this step is **mandatory**)_.
    1.  Currently, you are logged in as a `root` user and accessing `Admin Area`.
    2.  Navigate to `Account Information` > `List Accounts`.
    3.  Create your first User Account to access the `User Area`.
    4.  Now, login into your User Area with the user account that you just created.
    5.  In User Area, you can add your Domains, Email Accounts, Databases, and all other stuff


**You are all set. Enjoy your new ZesleCPv3 Control Panel.**
