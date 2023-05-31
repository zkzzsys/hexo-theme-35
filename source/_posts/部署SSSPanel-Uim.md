---
title: 部署SSPanel V3 魔改再次修改版
tags:
  - SSPanel V3 魔改再次修改版
categories:
  - 源码搭建
date: 2022-10-10 11:11:11
updated: 2022-12-10 11:11:11
---
<h1>SSPanel UIM</h1>

>越过长城我们可以到达世界的每一个角落</br>
>Across the Great Wall we can reach every corner in the world</br>

## 简介

SSPanel UIM 是一款专为 Shadowsocks / V2Ray / Trojan 协议设计的多用途代理服务销售管理系统。

## 特性

- 集成 支付宝当面付，Stripe 银行卡，彩虹易支付 等多种支付系统
- 支持多种邮件服务，内置队列功能，无需第三方组件即可使用
- 内置基于 Bootstrap 5 的 tabler 主题，Smarty 模板引擎支持
- 支持 Shadowsocks 2022，Shadowsocks AEAD，Trojan-Go 等最新代理协议
- 通用订阅接口，一键 json/clash/sip008 格式订阅下发
- 自定义节点配置，模块化订阅系统，支持多种传统订阅模式

## 安装

SSPanel UIM 的需要以下程序才能正常的安装和运行：

- Git
- Nginx（必须使用 HTTPS/HTTPS is REQUIRED）
- PHP 8.1+ （推荐开启 OPcache/OPcache is recommended）
- MariaDB 10.6+（关闭严格模式，不兼容 MySQL/Disable strict mode, DO NOT USE MYSQL）

我们推荐用户在开始使用之前至少有一定程度的 PHP 和 Linux 使用知识，能够至少正确识别使用中所出现的问题并在 issue 中提供所需的信息。

对于拒绝阅读文档且拒绝提供任何反馈的，我们建议其使用其他非开源的方案。

## 文档

> 我们安装，我们更新，我们开发

[SSPanel UIM Wiki](https://wiki.sspanel.org)，在这里你可以找到大部分问题的解答。

## 项目

SSPanel-UIM 不单单是一个面板，它还包括了一系列周边项目来帮助你更好的使用它。

你可以在 [SSPanel UIM 项目组](https://github.com/sspanel-uim) 的页面查看由我们的开发者维护的其他项目。


