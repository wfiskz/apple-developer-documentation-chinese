###苹果文件系统指南
####介绍
**重要： ** 本文档包含有关开发中的API或技术的初步信息。 该信息可能会发生变化，根据本文档实施的软件应使用最终的操作系统软件进行测试。

苹果文件系统是iOS，macOS，tvOS和watchOS的全新现代文件系统。它针对Flash / SSD存储进行了优化，并具有强大的加密功能， copy-on-write （写时数据） 元数据，空间共享，文件和目录的克隆，快照，快速调整目录大小，atomic safe-save primitives(原子安全保存)，以及改进的文件系统基础知识。

APFS将HFS +替换为iOS 10.3及更高版本的默认文件系统，以及MacOS High Sierra及更高版本。

####前提
要了解应用程序如何与文件系统进行交互，请参阅“[文件系统编程指南](https://developer.apple.com/library/content/documentation/FileManagement/Conceptual/FileSystemProgrammingGuide/Introduction/Introduction.html)”。
