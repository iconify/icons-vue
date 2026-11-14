<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s8twvn0_r"/><path class="s099_6b5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-filter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s099_6b5e {
  d: path("M13.611 14.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 14.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255q-.013-.128-.013-.257v-.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h9.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v.75q0 .349-.091.685t-.267.638M5.5 14.5V17M16 16h5.5l-2 2.75v2.75l-1.5-1v-1.75Z");
}

.s8twvn0_r {
  d: path("M4.5 8.5L6 4.25q.25-1 1.5-1h5q1.25 0 1.5 1l1.5 4.25");
}

</style>
