# Introduction

I learnt Rust purely out of [curiosity](https://www.linkedin.com/posts/joseph-udonsak_rustlang-softwareengineering-softwaredevelopment-activity-7026862841705938944-e57I?utm_source=share&utm_medium=member_desktop). At the moment I'm enjoying the process of taking on simple challenges and re-writing previously executed projects in Rust - just to get a feel for the language. 

Here's a list of some Rust projects I worked on. 

## CLI
For this project, I used [Seahorse](https://github.com/ksk001100/seahorse) to build a CLI for simple encryption/decryption. Cobra was useful for arranging the commands, and flag/argument parsing. 

In addition to encryption and decryption, I added a flag which takes a phone number. Where provided, the CLI sends a WhatsApp message with the encrypted content to the provided phone number. 

You can view the project repository [here](https://github.com/ybjozee/Seahorse_CLI). You can also read the accompanying tutorial [soon](#)

## [Cross platform desktop application](https://www.twilio.com/blog/build-a-cross-platform-desktop-application-with-rust-using-tauri)

For this project, I used [Tauri](https://tauri.app) to build a Github desktop client. The client interacts with the Github API to perform the following tasks:

1. View public repositories and Gists
2. View private repositories and Gists for an authenticated user
3. Create a new Gist for the authenticated user

For the frontend, I used React while I used Go for the backend.

You can view the project repository [here](https://github.com/ybjozee/Tauri_GitHub_Demo). You can also read the accompanying tutorial [here](https://www.twilio.com/blog/build-a-cross-platform-desktop-application-with-rust-using-tauri)

