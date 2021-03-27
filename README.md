# hacker-chat
Create a API if you can create a room for chatting with anyone

# How use:

You need node ^15.11

In terminal (no matter what folder): 

```
npm i -g @ygumattos/new-hacker-chat-client
```

Now you have de project in your PC, for use the chat: 

```
hacker-chat \
   --username YOURUSERNAME \
   --room YOURROOM \
```
**For example:**
```
hacker-chat \
   --username ygumattos \
   --room sala01 \
```



# For developer:

You need node ^15.11

Each folders there's a differents node projects. 

## In server folder:

```
npm ci --silent && npm run dev
```
## In client folder:

```
npm ci --silent
```
In package.json exists users' commands for tests, such as: 

```
npm run user01
```

