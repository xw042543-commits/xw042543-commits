<h1 align="center">Wang Xin</h1>

<p align="center"><strong>Building reliable software across embedded devices, Linux systems, and mobile products.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++20">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
</p>

## Currently building

### [EdgeLink](https://github.com/xw042543-commits/EdgeLink) — C++20 Linux device gateway

An event-driven gateway for receiving telemetry from embedded devices over a reliable
binary TCP protocol. The Linux software path is complete and tested with concurrent
simulators; ESP32 and SHT30 hardware integration is now in progress.

`C++20` `Linux` `TCP` `epoll` `CRC-32` `ACK & heartbeat` `CMake` `GitHub Actions`

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/xw042543-commits/EdgeLink">EdgeLink</a></h3>
      <p>A Linux device communication gateway with non-blocking I/O, stream recovery, delivery acknowledgments, heartbeats, reconnect logic, and concurrent load testing.</p>
      <p><code>C++20</code> <code>Linux</code> <code>epoll</code> <code>TCP</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/xw042543-commits/BiteBuddy">BiteBuddy</a></h3>
      <p>A nutrition management application with dedicated user, vendor, and administrator workflows.</p>
      <p><code>Flutter</code> <code>Firebase</code> <code>Riverpod</code> <code>GoRouter</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/xw042543-commits/LedgerKV">LedgerKV</a></h3>
      <p>A persistent key-value store with concurrent access, WAL recovery, TTL expiry, checksums, and compaction.</p>
      <p><code>C++20</code> <code>Concurrency</code> <code>Persistence</code> <code>CMake</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/xw042543-commits/AirportSimulation">Airport Simulation</a></h3>
      <p>A multithreaded simulation coordinating runways, gates, emergency priority, and shared resources.</p>
      <p><code>Java</code> <code>Concurrency</code> <code>Synchronization</code> <code>OOP</code></p>
    </td>
  </tr>
</table>

## Engineering focus

| Area | Tools and concepts |
|---|---|
| **Embedded and device communication** | ESP32, sensors, TCP protocols, device state, reliability |
| **Systems programming** | C, C++20, Linux, concurrency, `epoll`, persistence, file I/O |
| **Application development** | Flutter, Dart, Firebase, REST APIs, databases |
| **Engineering workflow** | Automated testing, debugging, CMake, Git, GitHub Actions |

## What I am working toward

I am developing EdgeLink from a tested software gateway into a real hardware system:

```text
SHT30 sensor → ESP32 → Wi-Fi/TCP → Linux C++ gateway
```

The next stages add telemetry storage, monitoring, multiple physical devices, and an
RS485/Modbus sensor path for industrial communication.

<p align="center">
  <a href="https://github.com/xw042543-commits?tab=repositories"><strong>View all repositories →</strong></a>
</p>
