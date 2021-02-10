---
marp: true
paginate: true
---

<!-- paginate: false --> 

**To the reviewer:** We build cars. A lot. In our plant it is one car every minute.

And we still deliver outstanding value and quality. All. The. Time. On demand.

---

**Also to the reviewer:** I will not do a color fuuuu power point. 

---


---

# What if we could build our software like... <br>...we build our cars?

(by using robots to automate all the things)

---
<!-- paginate: true --> 

# We build our cars using robots cause they...

- ensure high quality cause they are never
  - in a rush so they (are forced to) skip tasks
  - bored or tired so they forget something
  - demotivated 
- are less expensive than manual labor
  - set them up once and let them do their work automatically - forever
  - reduce rework cost cause they always do their job perfect
- free highly qualified worker 
  - so they can work on the improvement of the overall process
- look cool and might attack us if Skynet(TM) goes online.

---

# Intermezzo I


There is a nice term that describes what we do: its *Software craftsmanship*.
<br>
For me it shows a deep understanding that our work is like the one done on the production line: *we build something with value and quality in it by using our hands* (some of us also use their brain).

---

# but we still "build" our software by hand ...

Building software does not just mean 'write a program' - its more like building a car:
- at the beginning there is a line that creates a piece of value: the program
- while creating this, a lot of small manual tests are done on each little piece we created to build the even bigger / final one
- then it moves to the "final assembly stage": a bunch of people checks manually if everything was assembled correctly, engine starts and brakes are in place
  - as this is manual labor it tend to be expensive and ... error prone
  - in contrast to the cars: we might skip some tests if there is no time left (yes we always feel bad about this)

---

# Intermezzo II

The worst bug is an escaped bug - a bug in production.

Its like calling back 100.000 cars cause of a broken cable. 

Your customers will hate it (even if you pay for it) and they loose trust. 

And in any case it is freaking expensive. 

Exactly the same applies to software.

---

# ... and we even ship it by hand too.

- Imagine you would need to ship the 2.520.307 cars we build in 2019 by hand
  - some cars might get damaged or lost
  - some might arrived at the wrong place
- ...so lets repeat: manual labor is expensive and (sometimes) error prone
- same applies if you need to deploy software
  - it takes a lot of manpower to do this boring task (and not all "employees" are good "deployees")
  - the manual process just takes to much time
    - provisioning of all our plants takes a week 
      - but we could deliver a new feature
      - ...and emergency changes that took too long will add risk in our production (I do not want to explain the stakeholders why the revenue is smaller than predicted cause of... IT)

---

# The car monitors itself...

- even after the car is send to the happy customer it continues to monitor itself and reports its state to the central maintenance prediction services
  - I know - an alarm here is an outstanding event cause our quality is awesome.
- but our software sometimes... suffers from engine failures, brakes activate without any reason
  - ...sometimes it just explodes
- without all of the telemetry a car sends 'home' we
  - can not act proactively (no predictive maintenance possible)
  - need longer to explain to our customer what went wrong <=>
  - get longer and therefore more expensive down times (one car a minute!)

---

# and finally: we collected some numbers

We always had the feeling that we spend a lot of time on repetitive or error prone task.
Our bellies have been right - that's  "_what we spend our time on_" for the past 3 months:

| what                                                   | % of our time |
|--------------------------------------------------------|---------------|
| deployment                                             | 18            |
| fix broken deployments                                 | 12            |
| run (integration) tests                                | 33            |
| talk to the users  to explain why something  is broken | 2             |
| coding new features - create value                     | **35** :-(    |


--- 

# WHAT MAKES THE ROBOT IN SOFTWARE PRODUCTION?

### **CICD:** Continuous Integration + Continuous Deployment = Continuous Delivery

- Continuous Integration: build, integrate and test the software automatically
- Continuous Deployment: ship the software and their dependencies (e.g. infrastructure) automatically
- Continuous Delivery: continuous flow of new value with high quality to the customer


And as we are not perfect: 

### **MONITORING:** extract, collect and observe metrics - about everything

---

# benefits - big picture

## We will ship faster, more reliable, with higher quality and at less costs. And you can trust our software products like our customers trust our cars.

--- 
# benefits - for the DevOps teams

Like in vehicle production the use ofo robots has a direct impact on the (line) worker:
- the human employees could do other creative tasks
  - implement new features instead of doing robo-tasks
  - saving money by improving processes
  - think about / plan new features
- ...and at the same time employees will be more happy
  - no boring tasks
  - no avoidable mistakes (...uhh, blame culture...)
  - may increase motivation and reduce fluctuation


---

# HOW MUCH WILL IT COST?

- there will be an initial peak
  - developers might need to learn a few new tricks
    - must of us are highly motivated cause it will free us from rob0-task
  - we need to implement a few basic things
    - bit of infrastructure
    - an automation pipeline that models our production process
- ... so we think four man weeks over the next three months and a dedicated CICD server will do.
- in the long term we save as soon as we freed Devs from running tests or deployments manually - every seconds counts!

---

# implementation road map

We will not be able to stop the bleeding right now but
- we will define, monitor and report metrics to show the speedup and improvements we achieved
- we can setup the basic infrastructure pretty fast as we use standard tools
- we know the tasks that causing the most errors or take much time: automate first to save time and money now.
- allign new development to new CICD strategy, e.g. lets start to implement new integration tests so we can run them automatically: do it once - do it right.
- we will select a few Devs to do deep dives on the required topics so they can guide the initial implementation and spread the knowledge by doing
- instrument any new feature with metric exporters so we can use them now to do manual checks and later in our automated telemetry setup

---

# LETS AUTOMATE ALL THE THINGS!
## LETS AUTOMATE ALL THE THINGS!
### LETS AUTOMATE ALL THE THINGS!
#### LETS AUTOMATE ALL THE THINGS!
##### LETS AUTOMATE ALL THE THINGS!
###### LETS AUTOMATE ALL THE THINGS!
