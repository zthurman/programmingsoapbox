# Programming Soapbox

This is a collection of stuff that I've learned over the 
years. I find these reminders helpful. I hope that you do 
too.

1. Most of programming is centered around using methods,
infrastructure and tooling that forces you and your team
to acknowledge all of the **implicit** assumptions *about* 
the code, and then to somehow make those assumptions 
**explicit** *in* the code.

2. The machine doesn't care about your ego, only your logic.

3. It's all just bits. Bits can't hurt you.

    1. Unless of course the bit that you just flubbed triggers an 
    output on a safety significant machine or subsystem that you 
    happen to be standing near. If that's the case, the bits might 
    just kill you. 

        1. Be cautious, be paranoid, take breaks. Think it through.
        It isn't worth dying over. No matter how many people are 
        standing over your shoulder using you as an excuse to not
        work and pretending to be grouchy about it.

4. Don't touch the wires if you can help it. They have this
annoying tendency to let the magic smoke out of the machine.
When that happens, it's very hard to put it back.

5. The K&R Chapter 5 Verse 1
    
    int x = 1, y = 2, z[10];
    int *ip;

    ip = &x;
    y = *ip;
    *ip = 0;
    ip = &z[0]; 

