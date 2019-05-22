# Rocket.Chat

Rocket.Chat is a popular open-source alternative to Slack (chat application).

The aim of this task is to run a replicated version of Rocket.Chat with `docker` such that there are a total of 4 containers:
1. One load balancer container (chose whichever load balancer you like the most)
2. Two Rocket.Chat containers
3. One MongoDB container (used by Rocket.Chat)

You should create a new public GitHub repository (do not fork this repo) and push your solution to it, including:
1. A `docker-compose.yml` file that has the required components.
2. A `README.md` file that can be followed to run the application by anyone who has `docker` installed on their machine.
  - It would also be good if the README includes a short description of any design choices you made, why they were made, and what alternatives you investigated.

You can spend as little or as much as time you like on this task. We estimate this task to take less than 2 hours.
