<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lq4jdvbta"/><path class="s75pm3sse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:green-hydrogen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lq4jdvbta {
  d: path("M17.636 12.491C16.199 8.071 11 2.5 11 2.5s-7 7.5-7 12q0 .172.008.343t.026.343q.017.171.042.341t.059.339q.033.168.075.335t.091.331t.108.326t.124.321t.139.314t.155.307t.169.299t.184.29q.095.143.198.281q.102.138.211.271t.224.26t.237.249t.249.237t.26.224t.271.211q.138.103.281.198t.29.184q.148.088.299.169q.152.081.307.155q.155.073.314.139t.321.124t.326.108t.331.091q.167.042.335.075q.169.034.339.059t.341.042t.343.026q.171.008.343.008q.779 0 1.54-.171q.76-.172 1.464-.506");
}

.s75pm3sse {
  d: path("M7.5 14.5A3.5 3.5 0 0 0 11 18m4-3c4 0 6.5 2.5 6.5 6.5c-4 0-6.5-2.5-6.5-6.5");
}

</style>
