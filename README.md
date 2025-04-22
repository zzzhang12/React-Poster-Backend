# React Poster Backend 

A simple JSON‑based REST API to support the [React Poster Demo frontend](https://github.com/zzzhang12/React-Poster-Demo) .  
Stores and serves posts from a flat JSON file.

---

## Overview

This backend exposes endpoints to:
- **GET**  `/posts`       → list all posts  
- **GET**  `/posts/:id`   → fetch a single post by ID 
- **POST** `/posts`       → add a new post  

It uses a plain `posts.json` file as its data store.

---

### 1. Clone & install

```bash
git clone https://github.com/zzzhang12/React-Poster-Backend.git
cd React-Poster-Backend
npm install
```
### 2. Run the server
```bash
npm start
```