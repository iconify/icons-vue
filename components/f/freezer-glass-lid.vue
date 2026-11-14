<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9arrabfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freezer-glass-lid" /></template>
<style>
.m9arrabfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.883 4.5h12.234a1.5 1.5 0 0 1 1.312.772l.833 1.5A1.5 1.5 0 0 1 18.951 9H5.049a1.5 1.5 0 0 1-1.311-2.228l.833-1.5A1.5 1.5 0 0 1 5.883 4.5m6.728 14H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-4.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q4.996 9 5.125 9h13.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v2.132M7.5 12.5h5m5.5 2.25v6.5m-2.75-4.75l5.5 3m-5.5 0l5.5-3");
}

</style>
