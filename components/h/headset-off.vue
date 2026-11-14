<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlcyl2r0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headset-off" /></template>
<style>
.dlcyl2r0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12v-.5q0-1.106.341-2.158M9.06 5.147q.691-.319 1.435-.483Q11.238 4.5 12 4.5q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184q.143.095.281.198q.138.102.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343v.5M5.5 12zA2.5 2.5 0 0 1 8 14.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 16v-1.5A2.5 2.5 0 0 1 5.5 12m11.237.728q.174-.173.378-.309t.431-.23t.468-.141Q18.255 12 18.5 12q.123 0 .245.012t.243.036t.238.06q.117.035.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211t.105.221q.047.114.082.231t.06.238t.036.243t.012.245V16q0 .432-.145.839m-3.678 4.366q-.271.146-.57.22T16 21.5h-3.5m-9-18l17 17");
}

</style>
