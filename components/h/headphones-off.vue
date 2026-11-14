<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ki-6_ab7n"/><path class="tkvp0gb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headphones-off" /></template>
<style>
.ki-6_ab7n {
  d: path("M5 13.5v-1q0-.755.161-1.493t.476-1.425m4.181-3.733Q10.881 5.5 12 5.5q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184q.143.095.281.198q.138.102.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343v1m-16 0h5v7H3Z");
}

.tkvp0gb2z {
  d: path("M17.4 13.5H21v3.6m-4.4 3.4H16v-.6M3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
