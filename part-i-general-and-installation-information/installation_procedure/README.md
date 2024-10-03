# VENUS Software Installation Procedure

1. To back-up methods, etc., rename the Hamilton sub-directory to HAM or any other name that can easily be recalled. After doing so, proceed with the installation.
2. Insert the VENUS Software supplied on a USB Stick into a USB Port.
3. If the installation does not start automatically, select the SETUP.EXE program file found in the USB Stick. Follow the instructions during installation carefully.

<table data-header-hidden><thead><tr><th width="145"></th><th></th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (1) (1).png" alt="" data-size="original"></td><td><p>NOTE</p><p>VENUS Software is validated for the following Windows™ operating systems: Windows 7 (32-bit or 64-bit)</p><p>Windows 10 (32-bit or 64-bit)</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p>Administrator access to the computer must be allowed before any software installation.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p>Disable all antivirus programs before installation. Scripts used in the installation process can interfere with the virus protection software.</p></td></tr></tbody></table>

<table data-header-hidden><thead><tr><th width="145"></th><th></th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p><a data-footnote-ref href="#user-content-fn-1">When installing the software on Windows™ 7, make sure to set the “User Account Control Settings” to default.</a></p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p>As a safety precaution, before upgrading the system with the new software version, make sure to create back-up copies of the methods, user-defined labware, liquid classes, etc. The easiest way to do so is to export the method/workflows into a package file (refer to Method Export and Import).</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p>The installation may vary depending on the operating system used. Some necessary software prerequisites (delivered with VENUS Software) may require a reboot of the PC during installation.</p><p>If a software prerequisite is already part of the operating system, it will not be installed twice.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION</p><p>“Microsoft SQL Server 2014 SP2 Express Edition” has a limited storage capacity of 10GB.</p><p>Make sure that the SQL Server is maintained on a regular basis within routine use.isite is already part of the operating system, it will not be installed twice.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION </p><p>Remember to re-enable the virus protection software after successfully installing VENUS Software.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (23).png" alt=""></td><td><p>ATTENTION </p><p>If the option ‘Restrict functionality by user logon’ is used, access rights must be defined after software installation. See Section 2.4 Authentication Systems.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (1) (1).png" alt="" data-size="original"></td><td><p>NOTE</p><p>The chosen settings (except the selected instrument) are configurable via the Configuration Editor at a later time, if necessary.</p></td></tr></tbody></table>

## ‌InstallShield Wizard

<details>

<summary>1. Installation Preparation</summary>

1. The installation begins with certain preparation steps.\
   ![](<../../.gitbook/assets/image (4) (1).png>)

</details>

<details>

<summary>2. Microsoft SQL Server Installation</summary>

Using VENUS Software requires access to a Microsoft SQL Server. If the “Microsoft SQL Server 2014 SP2 Express Edition” is not installed at this point, a prompt will be displayed requiring a location and to access information from the Microsoft SQL Server after completion of the software installation.

1.  During installation, a prompt will be displayed asking if the SQL Server 2014 Service Pack 2 (SP2) shal be installed.

    <figure><img src="../../.gitbook/assets/image (5) (1).png" alt="" width="267"><figcaption></figcaption></figure>
2. Click \[Yes] to continue. If \[No] is chosen, please prepare the following information to be able to use another SQL Server:
   * Microsoft SQL Server Location
   * Database User Name and Password
3.  Click \[Next >] to continue.

    <figure><img src="../../.gitbook/assets/image (6) (1).png" alt="" width="378"><figcaption></figcaption></figure>
4.  Click \[Yes] to continue after the virus protection software and all other applications have been closed.

    <figure><img src="../../.gitbook/assets/image (7) (1).png" alt="" width="378"><figcaption></figcaption></figure>
5.  Click \[Yes] to continue.

    <figure><img src="../../.gitbook/assets/image (8) (1).png" alt="" width="378"><figcaption></figcaption></figure>
6.  If necessary, change the installation destination and click \[Next >] to continue.

    <figure><img src="../../.gitbook/assets/image (9) (1).png" alt="" width="378"><figcaption></figcaption></figure>

</details>

<details>

<summary>3. ‌Instrument Selection</summary>

1. Select the instrument from the dialog shown. This will install one of the following instrument deck layouts as the default layout.
2.  Click \[Next >] to continue.

    <figure><img src="../../.gitbook/assets/image (10) (1).png" alt="" width="378"><figcaption></figcaption></figure>
3.  Click \[Install] to continue with the installation process.

    <figure><img src="../../.gitbook/assets/image (11) (1).png" alt="" width="378"><figcaption></figcaption></figure>
4.  Specify the laboratory name and click \[Next >] to confirm the name.

    <figure><img src="../../.gitbook/assets/image (12) (1).png" alt="" width="378"><figcaption></figcaption></figure>
5. The installation of the VENUS Software will now start.

<img src="../../.gitbook/assets/image (13) (1).png" alt="" data-size="original">

\


</details>

<details>

<summary>4. ‌21 CFR Part 11 Security Settings‌</summary>

1.  The security requirements can be defined in the following screens:

    <figure><img src="../../.gitbook/assets/image (16) (1).png" alt="" width="378"><figcaption></figcaption></figure>

    1. **Restrict Functionality by User logon** \
       For more information about the controlled access functionality, refer to Section 2.4 Authentication Systems. The access rights of the current user are monitored. By installation default, it is set to: OFF
    2. **Record (all) File Names in the Runtime Trace**\
       All the linked file names such as deck layout, liquid classes, labware, etc. are logged (Log File) at the end of each method run. By installation default, it is set to: OFF
    3. **Use File Checksums to Validate Files** \
       Verify the checksum of the method and of all the linked files such as the deck layout, liquid classes, labware, etc. If a file is corrupted, the software will detect it. Enable/disable checksum verification of files. By installation default, it is set to: ON If "Record (all) file names in the runtime trace" is selected, the screen shown below is displayed.\

2.  Click \[Finish] to complete the installation.

    <figure><img src="../../.gitbook/assets/image (17) (1).png" alt="" width="378"><figcaption></figcaption></figure>
3.  Select the security requirements that are needed and click \[Next >] to continue.\


    <figure><img src="../../.gitbook/assets/image (18) (1).png" alt="" width="378"><figcaption></figcaption></figure>



    1. **Enable Versioning and Validation of Files**\
       By installation default, it is set to: OFF
    2. **Enable Viewing of File History**\
       By installation default, it is set to: OFF \
       If "Enable viewing of file history" is selected, the screen shown below is displayed. 4. Select the security requirements that are needed and click \[Next >] to continue. • Force Audit Trail for All File Changes By installation
4.  Select the security requirements that are needed and click \[Next >] to continue.

    <figure><img src="../../.gitbook/assets/image (19) (1).png" alt="" width="378"><figcaption></figcaption></figure>



    1. **Force Audit Trail for All File Changes** \
       By installation default, it is set to: OFF
5.  Click \[Finish] to complete the installation of the VENUS Software.

    <figure><img src="../../.gitbook/assets/image (20) (1).png" alt="" width="378"><figcaption></figcaption></figure>

\


</details>

<details>

<summary>5. ‌Support Software</summary>

After the successful installation of VENUS Software, the installation program for the Hamilton Support Software will start automatically.

1.  Select the labware, libraries and methods which are needed for the daily work by ticking the appropriate boxes. Click \[Next >] to continue.

    <figure><img src="../../.gitbook/assets/image (21) (1).png" alt="" width="341"><figcaption></figcaption></figure>
2.  Click \[Install] to begin the installation of the selected features for the Hamilton Support Software.\


    <figure><img src="../../.gitbook/assets/image (24).png" alt="" width="378"><figcaption></figcaption></figure>
3.  The installation of the features will take a few minutes.

    <figure><img src="../../.gitbook/assets/image (25).png" alt="" width="378"><figcaption></figcaption></figure>
4.  Click \[Finish] to complete the installation of the Hamilton Support Software.\


    <figure><img src="../../.gitbook/assets/image (26).png" alt="" width="378"><figcaption></figcaption></figure>
5.  After the successful installation of VENUS Software, find the Version Information under “Windows -> Start -> All Programs -> HAMILTON -> Version Info”. This tool provides information about the currently installed VENUS Software.&#x20;

    <figure><img src="../../.gitbook/assets/image (27).png" alt="" width="360"><figcaption></figcaption></figure>

\


</details>



1. ### ‌
2.  ### ‌Authentication Systems‌

    \


    Hamilton provides two independent authentication systems for the Hamilton software:

    * Operating System Authentication System
    * Hamilton Authentication System

    \


    ![image](blob:https://app.gitbook.com/044084d6-7b99-438e-a657-eb5bce02ba4a)

    ATTENTION

    Access rights must first be defined for the “Lab Service[” before any changes can be made in the System Configuration Editor. Refer to the ](file:///Users/zdmilot/Downloads/VENUS%20four%20Programmers%20Manual-2.html#bookmark38)[Section ](file:///Users/zdmilot/Downloads/VENUS%20four%20Programmers%20Manual-2.html#bookmark38)2.4.2[ ](file:///Users/zdmilot/Downloads/VENUS%20four%20Programmers%20Manual-2.html#bookmark38)[Operating System Authentication System](file:///Users/zdmilot/Downloads/VENUS%20four%20Programmers%20Manual-2.html#bookmark38)[.](file:///Users/zdmilot/Downloads/VENUS%20four%20Programmers%20Manual-2.html#bookmark38)

    \


    1.  #### ‌Choosing the Authentication System‌

        \


        1.  Open the system configuration editor.

            \


            ![04](blob:https://app.gitbook.com/e67d5262-f763-4eef-8ae8-6a7942add883)

            \

        2. Proceed to “Security Settings” and specify the settings shown below.
        3. Click the “Function Protection” entry to enable it.
        4. Select the desired authentication system.
        5. Click the “File  Save Changes” Menu, to save the changes made.

        \


        ![image](blob:https://app.gitbook.com/897861b0-6f09-49b0-bc2a-6b0593540b60)
    2.  #### ‌Operating System Authentication System‌

        \


        VENUS Software has five different levels of access authorization.

        \


        | Group                                     | User                                 | Authorization                                                |
        | ----------------------------------------- | ------------------------------------ | ------------------------------------------------------------ |
        | “Lab Operator”                            | Routine User                         | Operators may run any method                                 |
        | “Lab Operator 2”                          | Routine User                         | Operators 2 may run any method and move elements on the deck |
        | <p><br></p><p>“Lab method programmer”</p> | Method Programmer Laboratory Manager | Method programmers may modify method and labware definitions |
        | <p><br></p><p>“Lab Remote Service”</p>    | LAN Manager PC Administrator         | <p><br></p><p>Remote Service</p>                             |
        | <p><br></p><p>“Lab Service”</p>           | Service Engineer Laboratory Manager  | Hamilton Trained Field Service Engineer                      |

        \


        1.  Start by navigating through the explorer. Right click on “Computer” and select “Manage” from the list.

            \


            ![image](blob:https://app.gitbook.com/1cfb28a3-2de1-41e6-8d58-0c773f1787cc)
        2.  The “Computer Management” Window will be displayed.

            \


            ![06](blob:https://app.gitbook.com/da1fceae-7813-4b08-92f5-6319c9c54522)

            \

        3.  Open “Local Users and Groups”.

            \


            ![07](blob:https://app.gitbook.com/d8e4064b-cb04-499e-99e5-54c6713e269a)
        4.  Click on “Groups“, to display the list of defined groups. Groups such as “Lab Operator“, “Lab Operator2“, “Lab Method programmer“ and “Lab Service“ can be found on the list.

            \


            ![08](blob:https://app.gitbook.com/5b47abe8-8149-4cdf-b027-7afd85cbf997)

            Here, all users engaged in routine laboratory work (members of the “Lab Operator” group) must be keyed in to obtain the appropriate access rights.

            \

        5.  Double-click on “Lab Operator”. The “Lab Operator Properties” window will appear. Click the

            \[Add] Button.

            \


            ![09](blob:https://app.gitbook.com/08d80f78-d9c0-4702-a249-5d9f83b48508)

            ![image](blob:https://app.gitbook.com/8126f439-4b55-40df-81e4-9bc1a944124b)

            ATTENTION

            Decide if the user is to be defined only locally or also for the domain (when the PC is in a network environment).

            \

        6.  On the “Select Users” Screen, click the \[Locations…] Button.

            \


            ![10](blob:https://app.gitbook.com/99f40809-a8ed-4e7a-a45d-e93f3820c36c)

            Select the correct “Location” source for the laboratory and click \[OK].

            \

        7.  The entry “From this location” in the “Select Users” Window is then filled in.

            \


            ![11](blob:https://app.gitbook.com/1008009d-a80b-4d3f-9f46-ed0fc237c326)

            \


            ![Originalbild anzeigen](blob:https://app.gitbook.com/604c501f-a88f-442c-8e8d-9235e27d888a)

            NOTE

            The content on the “Locations” Screen will be different for each customer location.
        8.  Click the \[Advanced] Button.

            \


            ![image](blob:https://app.gitbook.com/73313fd5-4344-4a15-b3f2-f947bef2dd2b)

            \

        9.  Either click \[Find Now], or type the complete name or the beginning of a name in the “Common Queries” Text Field, this will search for a matching name. Click \[OK].

            \


            ![30](blob:https://app.gitbook.com/6e6de513-de3c-4c18-81d7-5ff7a7166fb7)
        10. Once the name is found, select \[OK], and the person will be added to the “Select Users” screen.

            \


            ![15](blob:https://app.gitbook.com/75c209fd-47af-4530-b945-e1bc7ea1815f)

            \

        11. Repeat the previous steps to add additional names. Once all required names are included, click \[OK].
        12. The selected user will then be added to the members list. Click \[OK] to finish.

            \


            ![16](blob:https://app.gitbook.com/8c8ddf18-1edc-4ddf-8c85-e0c34a6020cb)
        13. After defining the access rights, log off and then log on again. Check that the installation was successful by logging on with every specified user.

        \


        ![image](blob:https://app.gitbook.com/d32d0e47-e138-4b37-8dfc-7b4236644337)

        ATTENTION

        Unregistered users cannot operate the VENUS Software – not even LAN administrators. The following error message is displayed in the case of unauthorized access attempts:

        \


        ![31](blob:https://app.gitbook.com/d33e0690-bf00-45c0-af0a-896db0793bf7)

        \

    3.  #### ‌Hamilton Authentication System‌

        \


        The Hamilton authentication system is a log-on system implemented by the Hamilton Software to apply user rights independently from the operating system.

        \


        ![image](blob:https://app.gitbook.com/fe9fdb70-1457-4ff2-91c9-7072c69afb55)

        ATTENTION

        The Hamilton authentication system does not comply with 21 CFR Part 11.

        \


        Hamilton Software has four different levels of access authorization.

        \


        | Group                                     | User                                 | Authorization                                                |
        | ----------------------------------------- | ------------------------------------ | ------------------------------------------------------------ |
        | “Lab Operator”                            | Routine User                         | Operators may run any method                                 |
        | “Lab Operator 2”                          | Routine User                         | Operators 2 may run any method and move elements on the deck |
        | <p><br></p><p>“Lab Method Programmer”</p> | Method Programmer Laboratory Manager | Method programmers may modify method and labware definitions |
        | <p><br></p><p>“Lab Remote Service”</p>    | LAN Manager PC Administrator         | <p><br></p><p>Remote Service</p>                             |
        | <p><br></p><p>“Lab Service”</p>           | Service Engineer Laboratory Manager  | Hamilton Trained Field Service Engineer                      |

        1.  Open the system configuration editor.

            \


            ![image](blob:https://app.gitbook.com/32c9b3a3-ef9a-4621-82ac-d6700eac8549)

            \

        2.  Proceed to the security settings. Click the text field beside the “Authentication System” label and select “Hamilton Authentication System” from the list.

            \


            ![18](blob:https://app.gitbook.com/f09a599e-e129-435c-ac67-306a9210d667)

            \

        3.  Click the “File  Save Changes” Menu, to save changes. A confirmation dialog will be displayed.

            \


            ![32](blob:https://app.gitbook.com/43bac447-ea63-4590-bf89-0ccbfecada5b)
        4.  If the system was installed without “Function Protection” (disabled by default) the “Security Settings” message dialog shown below will appear.

            \


            ![19](blob:https://app.gitbook.com/2e3e0190-e627-48ff-b5b6-4ac2157a6493)

            \

        5.  To save the settings, click \[Yes].

            \


            ![20](blob:https://app.gitbook.com/e3a4f77e-1c8f-4a84-9d2d-c8bd68e864b0)
        6.  Confirm that no other Hamilton applications are running by clicking \[Yes].

            \

        7.  To log in as administrator, type the user name and password of the default login:

            \


            ![21](blob:https://app.gitbook.com/e6e2e7be-291c-493e-a619-00894f46434f)

            User: administrator

            Password: Hamilton

            \


            ![Originalbild anzeigen](blob:https://app.gitbook.com/2dd21080-7b46-438c-9dbe-d8f671a9f7f3)

            NOTE

            Remember that user names and passwords are case-sensitive.
        8.  Proceed to the “Manage Users” Tab in the system configuration editor to define the user rights.

            \


            ![22](blob:https://app.gitbook.com/e08f2a79-4aef-427f-ba75-b36653d8b2e0)

            \

        9.  Go to “Action  Create new User”

            \


            ![23](blob:https://app.gitbook.com/2c9716cc-fe87-4075-883a-16161b37adcd)

            \

        10. Fill the text fields with the required information and click \[OK].

            \


            ![24](blob:https://app.gitbook.com/bcf09527-daa0-4b14-98b2-1e7310e7c5c3)
        11. The “Permissions” for the user can be changed at the bottom of the window after creating the user as highlighted on the image shown below.

        \


        ![image](blob:https://app.gitbook.com/9a34f643-9aff-4799-8f3c-7b97b62c55e9)

        \

3.  ### ‌Adding Labware and Libraries‌

    \


    If not all labware and libraries needed for the daily work are installed, or if there is a requirement for additional labware or libraries, add elements using either the Method Editor, the Deck Layout Editor or the HSL Method Editor. To add labware or libraries, follow the steps below:

    1. Select "Tools  Hamilton Support Software..." from the menu bar.
    2.  Select "Modify" on the welcome screen, then \[Next >].

        \


        ![C:\Users\cweber\Desktop\build.png](blob:https://app.gitbook.com/645e5beb-ca98-4531-9113-ddc16dbd4f4d)

        A dialog box which lists all installable components in a tree view appears.
    3. Click on a “![plus](blob:https://app.gitbook.com/0f23b442-9b33-4b8a-adc4-eb9cb9b302bc)” sign to open a branch and mark / unmark the required components by ticking the boxes.
    4. Click \[Next >] to install the selected items.

    | Group                | Content                                                                                                |
    | -------------------- | ------------------------------------------------------------------------------------------------------ |
    | Labware              | Labware (e.g. plate carrier, tip carrier, sample carrier)                                              |
    | Methods              | Methods                                                                                                |
    | HSL Libraries        | HSL Libraries                                                                                          |
    | Service Enhancements | System Debugger for HSL                                                                                |
    | Old Labware          | Labware delivered by older versions of Hamilton Vector / VENUS Software → possibly needed for upgrades |

    \


    ![Originalbild anzeigen](blob:https://app.gitbook.com/e39868d5-242f-4f76-a5de-a37e4d160d6a)

    NOTE

    A checkbox next to a plus sign does not mean that all possible selections in the tree structure below are also checked.

    \

4.  ### ‌File Structure‌

    \


    The installation creates the following default directory structure.

    \


    ![p43](blob:https://app.gitbook.com/617a5841-fca1-4b53-a3ef-44dad31cd4a7)

    The file consists of the following directories listed in the table shown below.

    \


    | Directory   | Contents                                                                                                        |
    | ----------- | --------------------------------------------------------------------------------------------------------------- |
    | Bin         | Executables, DLLs                                                                                               |
    | Config      | Configuration files                                                                                             |
    | Graphic     | Icons and bitmaps for the software                                                                              |
    | Labware     | Labware definitions                                                                                             |
    | Library     | HSL libraries of commonly used additional functions                                                             |
    | Logfiles    | <p>Communication traces Method traces (*.trc)</p><p>Sample tracking result and report files</p>                 |
    | Methods     | Methods (\*.med, \*.hsl) Deck layouts (\*.lay)                                                                  |
    | System      | HxElementCounter.mdb                                                                                            |
    | C:\Barcodes | In addition, this directory is used by the sample tracking to store Microlab AT-like barcode and register files |

    \


    ## ‌PART II: The Microlab STAR VENUS Software

[^1]: \
    ![](<../../.gitbook/assets/image (3) (1).png>)
