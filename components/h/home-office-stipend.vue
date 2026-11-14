<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pewufkbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-office-stipend" /></template>
<style>
.pewufkbjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.511 11.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 11.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q2.5 9.004 2.5 8.875v-3.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T2.7 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h8.75q.205 0 .408.032t.397.095q.196.063.379.155t.349.212t.312.264t.268.309t.216.347t.16.377M9.5 11.5v3m-2.25 0h4.5M2 17.25h20m-18 0v4.25m16-4.25v4.25m-5.75-11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5-1.25v2.5");
}

</style>
