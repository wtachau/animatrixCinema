Animatrix Cinema

A web vr application using altspace sdk.

Concept : 
The Animatrix is my favorite film. It consists of 9 animated episodes. The Wachowski siblings partnered with 6 different animation studios in Japan, each studio taking responsibility for 1-3 episodes. The result is a collection of short stories told from various perspectives within the lore of the matrix.

Altspace has a beautiful cinema, set in space. While movie screenings have been successful, coming in late to a movie kind of sucks. The format of the animatrix and the disconnect between its episodes means that people joining the Animatrix screening late can still enjoy the episodes they get to see.

The most interesting film screening I've ever been to was for the perks of being a wallflower. Based on the book of the same name, it tells the story of a boy going through a year of high school. The author of the book is also the director of the film, and at this screening he was introduced after the movie to take Q/A from the audience. It was a unique experience to hear the creator talk about his work and interact directly with the audience.

Here is the idea for my animatrix app. Imagine being in the cinema having joined the "Animatrix Screening" event through a menu in altspace (or a link in any Web browser that launches altspace). When you enter the space, you see that the film hasn't started yet, and people are mingling. On the walls of the hallway are photos from the animatrix and any information (e.g. animation studios or episode names and which order they'll be played in) about the film or the event.

Setting this much up just means loading a bunch of objects and setting their textures to .png files we download from the internet, then manually (kind of painfully) positioning them in the environment. This will allow us to cover loading objects of (mostly) arbitrary shape and texture.

Next, it would be nice to give a small intro talk between each episode (or group of episodes, if done by the same studio), especially if people arrive midway through the event. During this intro, it would be cool to spawn relevant objects, pictures, or media and be able to click to expand or show or introduce behavior on the objects that respond to click events. This will allow us to cover handling click events (input from users) and state synchronization (to make sure everyone sees the same
thing at the same time.)

I'd love to flesh out this project over the course of time and eventually find a way to show the Wachowskis. It would be AMAZING to have them (and maybe other people from the project) come into altspace and give part of the presentation themselves, but I don't know if they would be interested. If I found out they had seen or heard about this event (like I record a video and they see it), that would be amazing. Like the rocky horror picture show, I could see myself slowly improving this app to
throw this event once a month, as well as throw it up on github so other people can build similar things for movies they enjoy.

We would start with a simple example application that gets us a spinning cube whose texture we can modify. I would send you the source to look it over but yall are locked out of the repo at the moment... I'm working on it.
