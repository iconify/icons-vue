<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pezo0ub_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headset-off" /></template>
<style>
.pezo0ub_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12v-.5q0-1.106.341-2.158M9.06 5.147q.691-.319 1.435-.483Q11.238 4.5 12 4.5q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184q.143.095.281.198q.138.102.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343v.5M3 12h5v6.5H3Zm13 .1V12h5v5.1m-3.823 4.105q-.271.146-.57.22T16 21.5h-3.5m-9-18l17 17");
}

</style>
