<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw-qlob2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headphones-off" /></template>
<style>
.aw-qlob2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5v-1q0-.755.161-1.493t.476-1.425m4.181-3.733Q10.881 5.5 12 5.5q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184q.143.095.281.198q.138.102.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343v1m-13.5 0zA2.5 2.5 0 0 1 8 16v2a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 18v-2a2.5 2.5 0 0 1 2.5-2.5m12.127.157q.423-.157.873-.157q.123 0 .245.012t.243.036t.238.06q.117.035.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211t.105.221q.047.114.082.231t.06.238t.036.243T21 16v1.073M3.5 3.5l17 17");
}

</style>
