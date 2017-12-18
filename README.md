# codein17notes
Here are my notes from projects I've done in Google Code-In 2017
# references
 * https://guides.github.com/features/mastering-markdown/
 # Task: movingblock-Develop a simple interface screen
  * First I cloned the Terasology repo
  
  * I used the command ./gradlew idea
  
  * I decided to use the sample module as a template rather than creating a module from scratch
  
  * I created a JSON file called "environmentInfoScreen.ui" with the code:
  ```   "type": "EnvironmentInfoScreen",
   {
    "type": "EnvironmentInfoScreen",
    "contents": {
        "type": "UILabel",
        "text": "Environment Info"
    }
}
```
* Got error "showScreen': java.lang.NullPointerException" in Terasology after running "showScreen environmentInfoScreen" in the console
