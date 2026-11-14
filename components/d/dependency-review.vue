<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2l9bcb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dependency-review" /></template>
<style>
.m2l9bcb2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h2.25A2.625 2.625 0 0 1 10 5.625v2.25A2.625 2.625 0 0 1 7.375 10.5h-2.25A2.625 2.625 0 0 1 2.5 7.875v-2.25A2.625 2.625 0 0 1 5.125 3m7.799 12.874q-.217-.184-.39-.412q-.172-.227-.292-.486q-.119-.259-.181-.537Q12 14.16 12 13.875v-2.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q14.496 9 14.625 9h2.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v2.032M6.25 10.5v2.25H12m2.5 5.75c1.75-3 5.25-3 7 0c-1.75 3-5.25 3-7 0m3.5 0h.01");
}

</style>
