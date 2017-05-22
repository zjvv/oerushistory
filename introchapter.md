

# Open Education Resources | How to Make Them Work
Ohio’s Education Technology Conference wrapped up this past week and my mind is buzzing with a good number of ideas and questions (always a sign of a good conference). I had the good fortune to sit on a panel to discuss Open Education Resources and, fresh off the fun conversations carried with other smart educators, wanted to brainstorm ways to make OER work in the education field. To some extent, tech conferences are about spotting trends (negative or positive) and my sense is that OER is beginning to really gain steam. 

## First, What are Open Education Resources
Open is the key word here. As in, resources are not restrictive. The internationalist in me likes the [Cape Town Open Education Declaration]:

>"Open educational resources should be freely shared through open licences which facilitate use, revision, translation, improvement and sharing by anyone. Resources should be published in formats that facilitate both use and editing, and that accommodate a diversity of technical platforms. Whenever possible, they should also be available in formats that are accessible to people with disabilities and people who do not yet have access to the Internet."

Licenses and copyrights run a range. Being good law abiding educators, we need to pay attention to those licenses and copyrights on materials we use to teach students. Open Education Resources make this possible. More importantly, OER allows us to build on what others have created.

## But OER has some Challenges
OERs are not a panacea to education. I’m particularly struck by the following challenges:
1. Quality Control
2. Searchability and Indexing
3. Portability
4. Funding

Before Pearson cribs those talking points and starts having lunch with legislators, I wanted to explore those issues in greater detail and suggest some solutions.

### On the Issue of Quality Control
Why a textbook? Sure, it’s nice to have resources. But our rockstar teachers are constantly curating and creating resources to fit the academic needs of their students. They don’t necessarily need a publisher’s textbook. So why buy them?

We buy them for quality control. For beginning teachers or teachers who struggle in the profession, textbooks provide a uniformed experience for students. These experiences might not be super rigorous or engaging, but at least the materials have been vetted by experts and are common.

Because OERs can and are created by anyone, they don’t necessarily have a quality control mechanism built in. That open textbook might have been written by a[writebot ]gleaning information off a reddit page. I’ve seen a lot of shoddy OERs (usually with bad clip art and lots of Comic Sans, which is odd).

**Now ideally and fundamentally, a teacher provides the quality control for their resources. They’re the expert. Trust them. And I do. Most teachers I work with are incredible.**

But teachers are also overworked. Sometimes they’re trying to get a quick worksheet fix before 5th period (I’ve been there). If there was a way to ensure quality in OERs, it would be a great help.

### Solution Ideas
**Define Authority**
Nothing new here, just a need to define “who” the authority is for reviewing an OER (beyond the teacher). The authority should have some type of credentials or proof that they are, in fact, an authority in the content area of the OER.

In Ohio, a number of organizations come to mind. InfOhio, ITCs, ESCs, various school consortiums, even (fingers crossed) the state. 

When authority is defined, some type of system also needs to be put in place to verify an OER is reviewed. 

**Wisdom of the Masses**
On the opposite side of defining authority is using the wisdom of the masses. In this type of system you have the masses up voting or down voting resources based on their quality. Similar to reddit, amazon reviews, or Digg.

This solution has its own challenges. First, you need critical mass to leverage the wisdom of masses. An OER watering hole where educators hang with fellow nerds. Second, sometimes the masses aren’t very wise (see Jaron Lanier’s [Digital Maoism: The Hazards of the New Online Collectivism]).

**A Hybrid**
The best solution would likely be a hybrid of sorts. A collective place to share and vote - but giving extra-weight to authority. Or possibly a curated collection of highest voted OERs. Wikipedia and [BetterLesson]have elements of this as well.

###Searchability & Indexing
How do I find quality OERs? Google isn’t necessarily the answer. Where do I direct teachers to find open education resources?

To some extent, InfOhio has laid some groundwork in this area with their iSearch feature (although this doesn’t necessarily search for OERs). Other organizations such as [OER Commons] and [Search Creative Commons] are making solid strides as well.

Personally, I would like the next level of searchability with an open API that allows districts to tie their curriculum platforms with a robust OER search engine.

###OER Portability
The largest issue I face as a technology director is the silo effect of systems. School districts are complex organizations with many moving parts. The parts need to talk with each other. Frequently they don’t.

The last thing I want is OERs to add to this complexity. Districts use different Learning Management Systems, Student Information Systems, Devices, Operating Systems, and personnel with different skill sets. OERs need to be as agnostic and portable as possible to account for these different conditions.

The question is how?

###Solution Ideas
This is not a new problem and others have put forth some solutions. SCORM, IMS Global, Tin Can API: All are possible approaches to a portable “unit” of learning. The geek in me really likes them. The pragmatist in me gets that their complexity prohibits widespread adoption. Your average teacher (much less technologist) is going to interface with an API. The problem is that this is very much a difficult problem to solve _without_ complexity. That said, we can look at popular models to get some ideas on how we might grow OERs.

Take OverDrive as an example. When I want to read **Thinking Fast, Thinking Slow** I follow this procedure:
1. Login to my library account
2. Click Overdrive
3. Select **Thinking Fast, Thinking Slow**
4. **Pick how I want to read the book.**

Step four is key. I’m given simple options: Amazon Kindle, ePub, web, PDF. While not exactly platform agnostic, the creator/publisher does pick the top 4 platforms (three of which are pretty open) to allow 95% of the market access to their content.

Were I a betting man, I would bet the development of OERs using web standards ([especially with the recent announcement of the merging of the two major consortiums W3C and IDPF]). Then the issue becomes how to “extract” an OER made with web standards into whatever flavor of platform a school or district uses.

One idea worth exploring (future post!) is a Git for OERs (and yes, I do realize I’m beginning to venture into complexity land here). The rough outlines of this idea:
1. An organization (lending credibility) hosts a git repository. Let’s call it gitedu.
2. Educators post their OERs to the git.
3. Other educators can contribute to the OER git. Report issues. Suggest corrections. Etc.
4. Or they can “fork” the OER into their own repository and take the OER in an entirely different direction.
5. The key is the OER inherits the same copyright and/or license.

While I get (pun intended) the software model of using Git with OERs might be a bit of a stretch (especially in education circles), there are definite function features within Git that would readily support the growth and adoption of OERs.

The key is keeping OERs as open as possible in their original form. I might create a Word Document worksheet and give it a Creative Commons License. It’s technically an OER. But if I want to build on that worksheet I really need to own Office. (This is a bit of a gray area. Microsoft would say that docx is technically an open XML format. But I’ve had many a Word Doc blow up when trying to open it with any other program other than MS Office).

###Funding Model(s)
Can OERs make money if they’re open? Or a slightly different question, can people creating OERs make money?

I would say yes.  It requires a different view on revenue.

First, I should point out that many of us who work on OERs are funded by tax dollars.  You can (and I do) make the case that OERs are the expected results of government investments. I personally think local, state, and federal governments would do well to invest into OERs through employing quality educators. It’s a better return on the dollars spent.

All that said, another model for funding would be to copy popular open-source platforms.

Take WordPress as an example. Anyone can download and run WordPress (for free). Yet WordPress has created a booming economy for many small and large businesses. It does this by:
1. Allowing businesses to provide support (revenue in labor).
2. Allowing businesses to offer “premium” add-on features.
3. Allowing businesses to offer “customizations”.

Say a future hypothetical OER Amazon begins to dominate the field. If OERs are open (anyone can use them), how does OERAma generate revenue to fund continual growth? They could:
1. Offer to host OERs on their own customized platform. Districts pay for access to the platform - the hosting if you will.
2. Offer customization on already existing OERs. Don’t like the cover image on an OER title? Pay $5 to update it to your school logo.
3. Offer scope of work to develop an OER from scratch. A district gets an OER at the of the work (with an open CC license), but they’ve paid for the labor of developing the OER.
4. Offer a subscription service for an OER. By joining the service, districts get updates on the OER (and a degree of support).

###The Wrap Up: Why OERs?

>Our own generation enjoys the legacy bequeathed to it by that which preceded it. We frequently know more, not because we have moved ahead by our own natural ability, but because we are supported by the menial strength of others, and possess riches that we have inherited from our forefathers. Bernard of Clairvaux used to compare us to punt dwarfs perched on the shoulders of giants. He pointed out that we see more and farther than our predecessors, not because we have keener vision or greater height, but because we are lifted up and borne aloft on their gigantic stature.
>_John of Salisbury_

Open is good for education. It allows students and teachers to build on previous knowledge without encountering the walls of proprietary knowledge silos. It allows districts to adopt and adapt resources to the particular needs of their students and communities without some of the worries that arise from copyright. 

OERs certainly have questions and issues that need addressing. It is my hope that the education community will work towards developing solutions that support their growth.




