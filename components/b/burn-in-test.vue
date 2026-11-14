<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdp7lbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burn-in-test" /></template>
<style>
.rtdp7lbaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.711 17H7.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T6.62 16.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q5 14.504 5 14.375v-6.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T5.2 6.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q7.496 5 7.625 5h6.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v4.232M9 2.5V5m4-2.5V5M2.5 9H5m-2.5 4H5m12-4h2.5M9 17v2.5m9.25 2a3 3 0 0 1-3-3c0-2 1.75-3 2.75-4c.25 1.5 1.5 1.75 1.75 1q1.5 1.5 1.5 3a3 3 0 0 1-3 3");
}

</style>
