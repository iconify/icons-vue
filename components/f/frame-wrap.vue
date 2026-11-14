<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmsq_p6hv"/><path class="hgvr-_b_p"/><path class="judnzd-wr"/><path class="ebq405bqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frame-wrap" /></template>
<style>
.ebq405bqc {
  d: path("M18.25 6.75L20 5l1.75 1.75");
}

.hgvr-_b_p {
  d: path("M9.625 7h3.75A2.625 2.625 0 0 1 16 9.625v3.75A2.625 2.625 0 0 1 13.375 16h-3.75A2.625 2.625 0 0 1 7 13.375v-3.75A2.625 2.625 0 0 1 9.625 7");
}

.hmsq_p6hv {
  d: path("M5.125 2.5h4.25A2.625 2.625 0 0 1 12 5.125v4.25A2.625 2.625 0 0 1 9.375 12h-4.25A2.625 2.625 0 0 1 2.5 9.375v-4.25A2.625 2.625 0 0 1 5.125 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.judnzd-wr {
  d: path("M7.5 20h9a3.5 3.5 0 0 0 3.5-3.5V5");
}

</style>
