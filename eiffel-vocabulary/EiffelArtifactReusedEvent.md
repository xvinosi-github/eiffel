<!---
   Copyright 2017 Ericsson AB.
   For a full list of individual contributors, please see the commit history.

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
--->

# EiffelArtifactReusedEvent (ArtR)
The EiffelArtifactReusedEvent declares that an identified [EiffelArtifactCreatedEvent](./EiffelArtifactCreatedEvent.md) has been _reused_ for an identified [EiffelCompositionDefinedEvent](./EiffelCompositionDefinedEvent.md). This means that it is logically equivalent to an artifact that would have been built from that composition, and can be used for build avoidance (see the [Build Avoidance Usage Example](../usage-examples/build-avoidance.md) for more information).

The event has no data members, but solely relies on its two required link types __REUSED_ARTIFACT__ and __COMPOSITION__ (see [The Links Object](../eiffel-syntax-and-usage/the-links-object.md)).

## Data Members

## Version History
| Version   | Introduced in                                          | Changes                                 |
| --------- | ------------------------------------------------------ | --------------------------------------- |
| 1.0.0     | [edition-bordeaux](../../../tree/edition-bordeaux)     | Initial version.                        |

## Examples
* [Simple example](../examples/events/EiffelArtifactReusedEvent/simple.json)
