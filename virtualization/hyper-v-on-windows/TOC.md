# [Introduction to Hyper-V](./about/index.md)
# [Install Hyper-V](quick-start/enable-hyper-v.md)
# [Make a Virtual Machine](quick-start/quick-create-virtual-machine.md)
# Manage Virtual Machines with Hyper-V
## [Hyper-V and PowerShell](quick-start/try-hyper-v-powershell.md)
## [Share devices with VMs](user-guide/enhanced-session-mode.md)
## [Work with Checkpoints](user-guide/checkpoints.md)
## [Connect with PowerShell Direct](user-guide/powershell-direct.md)
## [Create pre-release VMs](user-guide/create-pre-release-vm.md)
# Manage the Hyper-V Hosts
## [Enable Nested Virtualization](user-guide/nested-virtualization.md)
## [Set up a NAT network](user-guide/setup-nat-network.md)
## [Build an integration Service](user-guide/make-integration-service.md)
## [Port Hyper-V WMI](user-guide/refactor-wmiv1-to-wmiv2.md)
# Reference
## [Hyper-V Requirements](reference/hyper-v-requirements.md)
## [Supported Guest Operating Systems](about/supported-guest-os.md)
## [Hyper-V PowerShell](https://technet.microsoft.com/library/hh848559.aspx)
## [Hyper-V WMI Provider (V2)](https://msdn.microsoft.com/library/hh850319.aspx)
## [Hyper-V Integration Services](reference/integration-services.md)
## [Hyper-V Architecture](reference/hyper-v-architecture.md)
## [Windows Hypervisor Platform API](reference/hypervisor-platform.md)
### [WHvCancelRunVirtualProcessor](reference/hypervisor-platform-funcs/WHvCancelRunVirtualProcessor.md)
### [WHvCreatePartition](reference/hypervisor-platform-funcs/WHvCreatePartition.md)
### [WHvCreateVirtualProcessor](reference/hypervisor-platform-funcs/WHvCreateVirtualProcessor.md)
### [WHvDeletePartition](reference/hypervisor-platform-funcs/WHvDeletePartition.md)
### [WHvDeleteVirtualProcessor](reference/hypervisor-platform-funcs/WHvDeleteVirtualProcessor.md)
### [WHvGetCapability](reference/hypervisor-platform-funcs/WHvGetCapability.md)
### [WHvGetPartitionProperty](reference/hypervisor-platform-funcs/WHvGetPartitionProperty.md)
#### [Data Types](reference/hypervisor-platform-funcs/WHvPartitionPropertyDataTypes.md)
### [WHvGetRunExitContextSize](reference/hypervisor-platform-funcs/WHvGetRunExitContextSize.md)
### [WHvGetVirtualProcessorRegisters](reference/hypervisor-platform-funcs/WHvGetVirtualProcessorRegisters.md)
#### [Data Types](reference/hypervisor-platform-funcs/WHvVirtualProcessorDataTypes.md)
### [WHvMapGpaRange](reference/hypervisor-platform-funcs/WHvMapGpaRange.md)
### [WHvRunVirtualProcessor](reference/hypervisor-platform-funcs/WHvRunVirtualProcessor.md)
#### [Exit Contexts](reference/hypervisor-platform-funcs/WHvExitContextDataTypes.md)
#### [Memory Access](reference/hypervisor-platform-funcs/MemoryAccess.md)
#### [I/O Port Access](reference/hypervisor-platform-funcs/IOPortAccess.md)
#### [MSR Access](reference/hypervisor-platform-funcs/MSRAccess.md)
#### [CPUID Access](reference/hypervisor-platform-funcs/CPUIDAccess.md)
#### [Virtual Processor Exception](reference/hypervisor-platform-funcs/VirtualProcessorException.md)
#### [Unrecoverable Exception](reference/hypervisor-platform-funcs/UnrecoverableException.md)
#### [Unsupported Feature](reference/hypervisor-platform-funcs/UnsupportableFeature.md)
#### [Execution Cancelled](reference/hypervisor-platform-funcs/ExecutionCancelled.md)
### [WHvSetPartitionProperty](reference/hypervisor-platform-funcs/WHvSetPartitionProperty.md)
#### [Data Types](reference/hypervisor-platform-funcs/WHvPartitionPropertyDataTypes.md)
### [WHvSetupPartition](reference/hypervisor-platform-funcs/WHvSetupPartition.md)
### [WHvSetVirtualProcessorRegisters](reference/hypervisor-platform-funcs/WHvSetVirtualProcessorRegisters.md)
#### [Data Types](reference/hypervisor-platform-funcs/WHvVirtualProcessorDataTypes.md)
### [WHvTranslateGva](reference/hypervisor-platform-funcs/WHvTranslateGva.md)
### [WHvUnmapGpaRange](reference/hypervisor-platform-funcs/WHvUnmapGpaRange.md)
## [Windows Hypervisor Platform Instruction Emulator API](reference/hypervisor-instruction-emulator.md)
### Instruction Emulation
#### [I/O Port Access](reference/hypervisor-platform-funcs/IOPortAccessIE.md)
#### [MMIO Access](reference/hypervisor-platform-funcs/MMIOAccessIE.md)
### Emulator Structures
#### [WHV_EMULATOR_CALLBACKS](reference/hypervisor-platform-funcs/WhvEmulatorCallbacks.md)
#### [WHV_EMULATOR_IO_ACCESS_INFO](reference/hypervisor-platform-funcs/WhvEmulatorIOAccessInfo.md)
#### [WHV_EMULATOR_MEMORY_ACCESS_INFO](reference/hypervisor-platform-funcs/WhvEmulatorMemoryAccessInfo.md)
#### [WHV_EMULATOR_STATUS](reference/hypervisor-platform-funcs/WhvEmulatorStatus.md)
### API Methods
#### [WHvEmulatorCreateEmulator](reference/hypervisor-platform-funcs/WHvEmulatorCreateEmulator.md)
#### [WHvEmulatorDestoryEmulator](reference/hypervisor-platform-funcs/WHvEmulatorDestoryEmulator.md)
#### [WHvEmulatorTryIoEmulation](reference/hypervisor-platform-funcs/WHvEmulatorTryEmulation.md)
#### [WHvEmulatorTryMmioEmulation](reference/hypervisor-platform-funcs/WHvEmulatorTryEmulation.md)
### Callback Functions
#### [WHV_EMULATOR_GET_VIRTUAL_PROCESSOR_REGISTERS_CALLBACK](reference/hypervisor-platform-funcs/WHvEmulatorGetVirtualProcessorRegistersCallback.md)
#### [WHV_EMULATOR_IO_PORT_CALLBACK](reference/hypervisor-platform-funcs/WHvEmulatorIOPortCallback.md)
#### [WHV_EMULATOR_MEMORY_CALLBACK](reference/hypervisor-platform-funcs/WHvEmulatorMemoryCallback.md)
#### [WHV_EMULATOR_SET_VIRTUAL_PROCESSOR_REGISTERS_CALLBACK](reference/hypervisor-platform-funcs/WHvEmulatorSetVirtualProcessorRegistersCallback.md)
#### [WHV_EMULATOR_TRANSLATE_GVA_PAGE_CALLBACK](reference/hypervisor-platform-funcs/WHvEmulatorTranslateGVAPageCallback.md)
## [Hypervisor Specifications](reference/tlfs.md)
# Community and Support
## [Hyper-V forums](https://social.technet.microsoft.com/Forums/windowsserver/en-US/home?forum=winserverhyperv)
