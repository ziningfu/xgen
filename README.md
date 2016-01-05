# xgen
Welcome to xGen system!

<b>What is it?</b>

The system includes two main components, a new language, and a set of logic and architecture, which is designed to generate source code from the logic written in the language.

<b>What is its main advantage? How does it work?</b>

Java is claimed as "write once, run everywhere", well, with limitation - where Virtual Machine exists, and with features the bytecode requires. This system is designed to reduce the limitation - it can take the logic written in this language, generate source code in any language or language combination, regardless of versons, finally run anywhere, maybe after compilation if applicable. No VM is required.

<b>Hah? Too good to believe? Is it possible?</b>

A live sample is made in Wiki page:

https://github.com/ziningfu/xgen/wiki

You judge.

<b>Does this system depend on anything to support a new programing language?</b>

Yes. It depends on code generation rules.  To generate code in a target language in a target execution environment, the set of rules must exist for the target language and environment. Creating such a set of rules is not easy, but whole community can benefit once created.

<b>What does the new language look like?</b>

It is based on XML language, or say, it is a new instance of XML Schema. So it is not brand new.

<b>Why is a new language required?</b>

In short,  none of existing languages is independent of target execution environment to make this happen, but this language.

<b>Can we do the same with an existing language?</b>

Short answer is NO, as other languages all depend on some execution environment factors. It makes it hard to generate source code in some environments from a logic written by such languages.

<b>What does xGen mean?</b>

The "x" here means I'm not sure how to name the project yet. This repository is to demonstrate and disclose the design, and get some ideas from the community. There will be no real code with the repository but documentation only. Will create another repository once phase I coding is ready.

<b>How to contribute to xGen?</b>

Contributions to xGen are more than welcome! You will see how big it is. To support each target programing language, a set of code generation rules are required. Where are ways to reduce redundancy, but it will still be huge. Any knowledge in a specific field is much useful. Your name will be recorded as author or contributor for efforts you contributed. Together we will make a true change to the programing world.

<b>Is it too big to build?</b>

Don't worry. The core code of the project will be very small, say, hundreds or thousands of lines, and will be very stable. It will not change because of adding any new sets of rules for supporting new programing languages. Major efforts will be on building and debugging rules.
