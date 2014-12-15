msgrouter
=========

A process to route messages. Programming language usedis C#. Initial focus is on interfaces between the modules:

IMessageDepot
IMessageStorage
IMsgProcessingScheduler
IMsgProcessor
IMsgDeliveryScheduler
IMsgDeliveryHandler

The datatype is IEnvelope.
