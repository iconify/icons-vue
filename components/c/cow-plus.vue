<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyoajyszh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cow-plus" /></template>
<style>
.hyoajyszh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.811 12.5H9.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T8.62 12.3q-.119-.049-.232-.11t-.221-.132t-.207-.154q-.1-.082-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q7 10.004 7 9.875v-2.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T7.2 6.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q9.496 5 9.625 5h7.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v2.25q0 .188-.027.373q-.026.186-.079.366t-.131.351t-.179.328t-.224.3t-.265.265q-.141.123-.299.224t-.328.18M7 6l-3.25-.5l-1.25 5l2.5 1l2-1m-2.75-5L3.5 3m6 9.5V17m3.5-4.5v3.6m5-1.1v6m-3-3h6");
}

</style>
