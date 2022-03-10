# useReducer-guide

 1. We import use reducer


 2. We create the useReducer state inside the App function
  -state is refering to the count:0 object
  -dispatch is the kind of action we want to use to update the state
  
<img width="632" alt="Screenshot 2022-03-10 at 22 11 48" src="https://user-images.githubusercontent.com/74420607/157763547-362b9f34-b0e2-4825-b8ca-3f48b64e7059.png">
    
<img width="616" alt="Screenshot 2022-03-10 at 22 25 10" src="https://user-images.githubusercontent.com/74420607/157765148-4dcacafa-989c-414d-bcf9-513489500c8e.png">


    
 3. We crate an action variable  so we know how the action type is going to change the state
  
<img width="437" alt="Screenshot 2022-03-10 at 22 17 22" src="https://user-images.githubusercontent.com/74420607/157764254-ef684336-7da7-4bb0-b8ce-65bbaef0404a.png">


4. We create the function reducer that will contain the state (' the count ')as first parameter, and the action as second parameter,followed by a switch with an action.type.
  every case in the switch will refer to different action that will update the state differently

<img width="502" alt="Screenshot 2022-03-10 at 22 19 07" src="https://user-images.githubusercontent.com/74420607/157764387-f6b6111a-3705-4919-850b-f3bac470b88d.png">

5. Now we can call an anonymous function containing the dispatch with the type action selected

<img width="713" alt="Screenshot 2022-03-10 at 22 27 32" src="https://user-images.githubusercontent.com/74420607/157765670-16c94686-6d7c-4bb7-8f04-05afda2b93a0.png">

