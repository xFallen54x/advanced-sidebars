# Advanced Sidebars

<a href="https://github.com/xFallen54x/advanced-sidebars/blob/main/LICENSE">
  <img alt="GitHub" src="https://img.shields.io/github/license/xFallen54x/advanced-sidebars">
</a>
<a href="https://discord.gg/FN9gwVuE5S">
  <img alt="Official Discord Server" src="https://img.shields.io/discord/753438334663000116?color=%237289DA&label=Discord&style=flat-square">
</a>

## Why use Advanced Sidebars?

-   Ever wanted to make your own sidebar like the ones on Servers but don't know were to Start well this pack will help you make that come true.
-   Easy to setup

## Getting started

- The titleraw is what you will most likely be using for your sidebar. It uses rawtext json formating. The three componets you will be focusing on in your commands for the sidebar are **text**, **score**, and **selector**. Your best bet for making the sidebar will be using functions instead of commands blocks it will be much easier in the end. 
 
- Command Example for creating your sidebar execute @a ~~~ ***titleraw @s {"rawtext":[{"text":"§l§eFallen §bSkyblock \n §7Name: §b"},{"selector":"@s"},{"text":"\n §7Balance: §a$},{"score":{"name":"@s","objective":"Balance"}}]}***
  - ## How it works
    - The **text** componet will display as any normal text, but for your sidebar you will need multiple lines. Thats what **\n** is for as shown in the command example above. Most people already know this but for those who don't know this symbol **§** will allow you to color or format your text on your sidebar. 
      
          Example:  ***titleraw @s {"rawtext":[{"text":"line 1 \n line 2 \n line 3"}]}***
      
          **§** formating Examples: 
      
      <img alt="§" src="https://media.discordapp.net/attachments/789321466977976342/790010505410379826/OIP.jpeg?width=263&height=324">
    
     - The **selector** componet will display an entity's name. If you want to display the players name on their Sidebar you would use **@s**. (Will go more into detail later on, this could also be used to make suffixes for player scores. Example: ***10000 -> 10,000 or 10000 -> 10.00K***
     
           Example:  ***titleraw @s {"rawtext":[{"text":"Name: "},{"selector":"@s"]}***
     
     - The **score** componet will display a scoreboard objective. If you are going to display the users lets say "Money" you will set the **name** part of the componet to **@s** and the **objective** part to your "Money Objective"
     
           Example:  ***titleraw @s {"rawtext":[{"text":"Money: "},{"score":{"name":"@s","objective":"Money"}]}***
    
## How to edit Sidebar Placments

  ### Getting Started
   - Just warning you if you do not have any resource pack develoment knowledge this will be harder for you to understand.

   - First things first download the **Advanced_Sidebar.zip** and then unzip the files and move everything to a folder located somewhere on your computer that you can easily access. When this is complete you will want to navigate inside that folder to **ui** and the you will want to open the **hud_screen.json**. If you don't have a code editor on your computer I suggest you use ***Microsoft's Visual Studio Code*** (This will be linked down below).

   - After doing the first few steps. On your code editer to find what we are looking for press your **Ctrl** and then **F** key to open up a search bar. After doing so search for **hud_title_text** this is the component we will be changing. 
   
      - It should look something like this:
   
       <img alt="hud_title_text" src="https://media.discordapp.net/attachments/784646858197958706/790025966398734366/unknown.png?width=345&height=579">
   
   

## FAQ

## Remarks

