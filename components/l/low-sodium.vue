<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si7g5obvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:low-sodium" /></template>
<style>
.si7g5obvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.925 10h.45q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v.432m-.536 7.408q-.092.12-.197.229q-.104.109-.221.205q-.116.097-.243.179t-.262.149t-.278.118t-.289.086q-.148.034-.298.052t-.301.017h-4.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T8.62 21.3t-.232-.11t-.221-.132t-.207-.154q-.1-.082-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q7 19.004 7 18.875v-6.25q0-.339.086-.667q.086-.327.252-.622m1.28-6.687C9.51 3.892 10.699 3.5 12 3.5c2.75 0 5 1.75 5 5V10m-6-4.25h.01M13 5h.01M15 6.75h.01M3.5 3.5l17 17");
}

</style>
