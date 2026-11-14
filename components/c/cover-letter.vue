<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rq4-vabhd"/><path class="w1geybutg"/><path class="k2_66rb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cover-letter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2_66rb6q {
  d: path("M16.25 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 4.25h2.5m-2.5 3h2.5m-13.5 0h5.5m-5.5 3.5H9.5m-4-13za1.25 1.25 0 0 1 1.25 1.25v4A1.25 1.25 0 0 1 5.5 11a1.25 1.25 0 0 1-1.25-1.25v-4A1.25 1.25 0 0 1 5.5 4.5");
}

.rq4-vabhd {
  d: path("M9.525 7h1.35q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154q.1.082.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v9.25q0 .129-.013.257q-.012.129-.037.255q-.026.127-.063.25t-.087.243t-.11.232t-.132.221t-.154.207q-.082.1-.173.191t-.191.173q-.099.082-.207.154q-.107.071-.221.132q-.113.061-.232.11q-.12.05-.243.087t-.25.063q-.126.025-.255.037q-.128.013-.257.013h-5.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V12.78");
}

.w1geybutg {
  d: path("M9.75 7V4a1.5 1.5 0 0 1 1.5-1.5H20A1.5 1.5 0 0 1 21.5 4v11.5A1.5 1.5 0 0 1 20 17h-6.5");
}

</style>
