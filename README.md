# AuthSystem
DBM Project that Authenticates an user in a Discord Server

It reads the 'keys' (strings) from an online JSON and once a key is used, it deletes the used key from the array of keys available to be used. I made the bot save the list of keys locally so you don't need an API to edit the online JSON and this Auth System includes 3 'basic' commands:

• [p]authSave - Reads the keys from the online JSON and saves them locally. (Administrator)

• [p]authDisplay - Displays the keys that are available to be used. (Administrator)

• [p]auth [key] - Authenticates the user by giving them a Discord Role. (Everyone)

Feel free to tweak this to fit your needs by either adding a specific channel to work on or any other different actions you may want to perform with it.

You can contact me on Discord (Kirtle#0498) if you need any help.
Note: It probably requires DBM Beta and Mods. (Select the beta update on steam)
