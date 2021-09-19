# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [x] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF
Portrait and landscape mode:

<img src="https://media0.giphy.com/media/uXIDCNXuyfxJeS23B5/giphy.gif?cid=790b76114c39d46b60cd172e1829ef0a913338b7639af038&rid=giphy.gif&ct=g" width=''><br>

To test the placeholders, I slowed the emulator network speed. You can see the placeholders render and disappear quickly in this GIF:

<img src="https://media1.giphy.com/media/ctOOw7DVlWsUSDCmQQ/giphy.gif?cid=790b76110e11167bc40770a724ca12819947af749fbb2c9b&rid=giphy.gif&ct=g" width=''><br>

Here is a single frame from the GIF that captures the placeholders:

<img src="https://i.imgur.com/2HD1yNE.jpg" width='250'><br>


### Notes
I did not run into any issues or challenges. As an extra improvement to the UI, I included the release date with every movie.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
