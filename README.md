# Elevens-Card-Game
A classic card game of Elevens implemented in Java

First, set up the game by shuffling the deck and then laying nine cards face up while the others in a pile face down as the draw-deck. Start the game by removing any two cards with face values that add up to 11, or a set of one Jack, one Queen and one King. Discard them into the used pile. Next, draw two (or three, if a set of JQK was removed previously) new cards and replace the discarded ones so there are always nine cards facing up, unless the draw-deck is empty and there are no more un-discarded cards left. Repeatedly do this
until there are either no cards left and the player has won the game or when there is
nothing that can be removed/discarded, resulting in a loss.

The game does not involve any strategy, it is fully based on luck. Even though
sometimes there may be more than one move that can be done each turn, but it
doesn’t matter what order you do them in. Ultimately, it is the “replacing” step that
determine the player’s fate and there’s no way for the player to predict what cards
are coming next. Every card pairs up with another on a 1 to 1 ratio, so there is no
way to calculate or strategize a way to win.
