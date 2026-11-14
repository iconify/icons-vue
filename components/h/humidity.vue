<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rucykvbgr"/><path class="c01rp65rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidity" /></template>
<style>
.c01rp65rn {
  d: path("m15 16.5l3-3l3 3");
}

.rucykvbgr {
  d: path("M16.589 10.676C14.694 6.694 10.5 2.5 10.5 2.5s-7 7-7 11.5q0 .172.008.343t.026.343q.017.171.042.341t.059.339q.033.168.075.335t.091.331t.108.326t.124.321t.139.314t.155.307t.169.299t.184.29q.095.143.198.281q.102.138.211.271t.224.26t.237.249t.249.237t.26.224t.271.211q.138.103.281.198t.29.184q.148.088.299.169q.152.081.307.155q.155.073.314.139t.321.124t.326.108t.331.091q.167.042.335.075q.169.034.339.059t.341.042t.343.026q.171.008.343.008q.516 0 1.026-.076q.51-.075 1.004-.225q.494-.149.96-.37q.467-.22.896-.506M18 21.5v-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
