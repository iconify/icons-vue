<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pa9rt-yuz"/><path class="yihzly52s"/><path class="zf18g1a3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-seed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pa9rt-yuz {
  d: path("M2.5 5a7 3 0 1 0 14 0a7 3 0 1 0-14 0");
}

.yihzly52s {
  d: path("M2.5 5v9q0 .074.008.147q.009.074.026.147t.042.146t.059.145t.075.144t.091.142t.108.14t.124.137t.139.135q.074.066.155.131t.169.128t.184.125t.198.12t.211.116t.224.112t.237.106t.249.102t.26.096q.133.047.271.091q.138.043.281.084t.29.079t.299.073q.152.034.307.066q.155.031.314.06t.321.053t.326.046t.331.039t.335.032q.169.015.339.026t.341.018t.343.01Q9.328 17 9.5 17q1.159 0 2.256-.16m4.744-4.546V5");
}

.zf18g1a3b {
  d: path("M2.5 9.5a7 3 0 0 0 14 0m1.5 12v-4m0 1c0-2.5-1.75-3.75-3.75-3.75c0 2.25 1.5 3.75 3.75 3.75m0-1c0-2.25 1.5-3.5 3.75-3.5c0 2.25-1.5 3.5-3.75 3.5");
}

</style>
