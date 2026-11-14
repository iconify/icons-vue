<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kpr51l4fk"/><path class="vry5f4rlj"/><path class="ihw4hkidx"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grant-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihw4hkidx {
  d: path("M2.5 9.75a7 3 0 0 0 14 0M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.kpr51l4fk {
  d: path("M2.5 5.5a7 3 0 1 0 14 0a7 3 0 1 0-14 0");
}

.vry5f4rlj {
  d: path("M2.5 5.5V14q0 .074.008.147q.009.074.026.147t.042.146t.059.145t.075.144t.091.142t.108.14t.124.137t.139.135q.074.066.155.131t.169.128t.184.125t.198.12t.211.116t.224.112t.237.106t.249.102t.26.096q.133.047.271.091q.138.043.281.084t.29.079t.299.073q.152.034.307.066q.155.031.314.06t.321.053t.326.046t.331.039t.335.032q.169.015.339.026t.341.018t.343.01Q9.328 17 9.5 17q1.329 0 2.566-.209m4.434-4.697V5.5");
}

</style>
