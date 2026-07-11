# Netty Awards 2026 — voting demo

Demo build of Network Media's Netty Awards voting experience, hosted for testing.

- `index.html` — creator-facing voting site (donation gate → Golden Ticket → ballot)
- `admin.html` — Team Console: the Golden Ticket verification queue
- `netty-data.js` — nominee data (top 5 most-viewed videos per genre, past 12 months)

**Demo notes:** verification state and votes live in the browser's localStorage.
To test the full loop, open the voting site and the Team Console in two tabs of the
same browser. The Facebook login is mocked (no real Facebook connection); in
production it would be real FB Login + a small backend queue.
