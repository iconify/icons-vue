<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhos8yfuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-water-splash" /></template>
<style>
.jhos8yfuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.377 12.406C17.443 8.018 11.5 2.5 11.5 2.5s-7 6.5-7 11q0 .172.008.343t.026.343q.017.171.042.341t.059.339q.033.168.075.335t.091.331t.108.326t.124.321t.139.314t.155.307t.169.299t.184.29q.095.143.198.281q.102.138.211.271t.224.26t.237.249t.249.237t.26.224t.271.211q.138.103.281.198t.29.184q.148.088.299.169q.152.081.307.155q.155.073.314.139t.321.124t.326.108t.331.091q.167.042.335.075q.169.034.339.059t.341.042t.343.026q.171.008.343.008q.542 0 1.077-.083M18.5 15.25v6.5m-2.75-5l5.5 3.5m-5.5 0l5.5-3.5");
}

</style>
