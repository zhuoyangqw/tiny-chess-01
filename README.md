# tiny-chess-01

An original 4 KB Python chess engine, written from scratch for the
make.fun tiny-chess-01 bounty. 0x88 board, negamax alpha-beta with
iterative deepening under a fixed 120,000-node budget, transposition
table, killer moves, MVV-LVA ordering, quiescence over captures and
promotions, material plus piece-square evaluation with a tapered king
table and the bishop pair. Deterministic: no clock, no unseeded
randomness. It plays the house gauntlet through the env at
MAKEFUN_ENV_URL (POST /game, /move).

Practice Elo (6-game trials): 1654, 1654, 1545 — mean 1618.
