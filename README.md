# Project 3 Pitch

## Fork & Clone this repo.

Review the [Project 3 requirements](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/project-3#project-feedback-evaluation) and check out some [examples](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/past-projects/project3).

Provide information in the following sections:

---

### Project Overview

##### (Include project idea/concept, project name, who owns git master repo on github, team name [if desired], team member roles, elevator pitch)

## Project Idea/Concept ❥

- A full stack application that provides a safe and free community platform to share and express your voice as an artist, poet, lyricist but most of all a human being that expresses themselves, where self-expression and feeling human has been suppressed in these troubled times.

## Project Name ❥

### voiceS

- Your Voice, is my ›❤ Sound<br>

## Who owns git Master repo on github ❥

- Yoel Morad<br>
  [Yoel's gitHub](https://github.com/yoel0)

## Team Name ❥

> The W A R R I O R S<br>
> "Fire it up, what it taste like? LEMONADE when its made right.. you ain't never met nobody who sees the stars the way we do, nobody who can love you as much as we do.."<br> ![BangBANG](https://i.imgur.com/3XPcSRq.jpg)

## Team Member Roles ❥

- gitMaster / FrontEnd / BackEnd

  > Yoel "Sugar Honey Bunny" Morad<br> > [Yoel's gitHub](https://github.com/yoel0)

- Organizer / FrontEnd / BackEnd

  > Channee "Right Hand" Math<br> > [Channee's gitHub](https://github.com/chamon562)

- CSS Trickster / FrontEnd / BackEnd

  > Philip "Imperial Diamond" Yap<br> > [Philip's gitHub](https://github.com/philipyap)

- BackEnd Warlock / FrontEnd / BackEnd<br>

  > Nicholas "Maestro" Phillips<br> > [Nicholas's gitHub](https://github.com/maestronick1)

## Honey Sting/Stang (Elevator Pitch) ❥

People are often frustrated by the effort it takes to express their voice in a free and safe zone where they can be heard.
Our App eliminates the feeling of being imprisoned without a voice.
For years, people have trusted society to safe guard freedom of expression however time and time again they have found themselves.. their.. voice restricted.
With voiceS, you can express yourself freely and bring about creative freedom on a platform that not only values your voice but broadcasts it, with the power of community.

---

### Models and Schemas

** Models & Schemas **<br>
(A Model is a IMPLEMENTATION OF A SCHEMA! ye boi.)<br>
(Because a Schema is the representation of a model)<br>
(Recipe turned in to dishes)<br>
(Template to document)<br>
#FireSquad.

User

- Category
- Name
- Email
- Password
- Publications []

Publication

- User
- Category
- Name (of Publication)
- Content
- Comments []
- Reactions []

Comment

- User
- Content
- Publication

Reaction (Stretch but a really needed stretch for the honey effect)

- User
- Type (of Reaction)
- Publication

---

### User Stories

> As a User I can Signup / Login.<br>
> As a User I can publish my creative content.<br>
> As a User I can view other Users creative content.<br>
> As a User I can Edit / Delete my own creative content.<br>
> As a User I can comment on creative publications and Edit / Delete Comments.<br>
> As a User I can react (reactions/type of likes) to creative publications.<br>

---

### Wireframes

- Home Page<br>
  ![Home Page](https://i.imgur.com/dVYrbLi.png)
- Signup Page<br>
  ![Signup Page](https://i.imgur.com/kfl4akV.png)
- Login Page<br>
  ![Login Page](https://i.imgur.com/myt4h5t.png)
- Profile<br>
  ![Profile Page](https://i.imgur.com/vuF7Ejm.png)
- Community page<br>
  ![Community Page](https://i.imgur.com/0kw3fQN.png)

---

### Additional Technologies

## Planned Technologies

- MERN STACK
  - MongoDB
  - Express
  - React
  - Node

* Bootstrap 4

* JSX (lol)

* Github Project (Kanban Board, set team members as contributors)

## Optionals (Subject to Change at discretion of Team W A R R I O R S)

- Cloudinary (May<-- May have User Profile Pics)

##### (MERN Stack expected [MongoDB, Express, React, Node], include any external APIs)

---

### Work Allocation

##### Who is your Gitmaster? Who will be doing what?

- gitMaster / FrontEnd / BackEnd

  > Yoel "Sugar Honey Bunny" Morad<br> > [Yoel's gitHub](https://github.com/yoel0)

- Organizer / FrontEnd / BackEnd

  > Channee "Right Hand" Math<br> > [Channee's gitHub](https://github.com/chamon562)

- CSS Trickster / FrontEnd / BackEnd<br>

  > Philip "Imperial Diamond" Yap<br> > [Philip's gitHub](https://github.com/philipyap)

- BackEnd Warlock / FrontEnd / BackEnd<br>

  > Nicholas "Maestro" Phillips<br> > [Nicholas's gitHub](https://github.com/maestronick1)

---

### Daily Sprints

- September 4, 2020 Friday

  - Standup 7:00PM to 9:00PM PST
  - Set Up Server and Client Repo and Dependencies
    (if, time scrub out models) else {res.send(Sprint2)}

- September 5, 2020 Saturday
  - Standup 12:00PM
  - Work TBD based off Standup
- September 6, 2020 Sunday
  - Standup 12:00PM
  - Work TBD based off Standup
- September 7, 2020 Monday (Labor Day)
  - Standup 7:00PM
  - Work TBD based off Standup
- September 8, 2020 Tuesday
  - Standup 9:00AM
  - Work TBD based off Standup
- September 9, 2020 Wednesday
  - Standup 9:00AM
  - Work TBD based off Standup
- September 10, 2020 Thursday (Deployment)
  - Standup 9:00AM
  - Work TBD based off Standup
- September 11, 2020 Friday (Presentations)
  \n yebb.

##### (or otherwise general plan for accomplishing tasks, preferably broken down by day)

---

## Make a PR when you're done!

# Full Stack Your Voice, is my ›❤ Sound

A full stack application safe and free platform to share and express your voice as an artist, poet, musician but most of all a human being in these troubled times where self-expression and feeling human has gotten lost in translation.

### TODO

- [ ] Setup Server
  - [ ] Install Dependencies
  - [ ] Install / Setup Linter
  - [ ] Setup Express App
  - [ ] Setup Not Found and Error Middlewares
- [ ] Model DB
  - What data will we store?
- [ ] Setup Mongoose Model(s)
- [ ] Setup Routes
  - What routes will we have?
- [ ] Setup Client
- [ ] DEPLOY it like its HAWT!
