<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1wg2i63c"/><path class="bc-78tcbw"/><path class="eqey0fxvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-court" /></template>
<style>
.b1wg2i63c {
  d: path("M6.625 2.5h10.75A2.625 2.625 0 0 1 20 5.125v3.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 8.875v-3.75A2.625 2.625 0 0 1 6.625 2.5");
}

.bc-78tcbw {
  d: path("M6 13a6 1.5 0 1 0 12 0a6 1.5 0 1 0-12 0m4.5-7.5h3A1.5 1.5 0 0 1 15 7v.5A1.5 1.5 0 0 1 13.5 9h-3A1.5 1.5 0 0 1 9 7.5V7a1.5 1.5 0 0 1 1.5-1.5");
}

.eqey0fxvh {
  d: path("M6.5 13.5L9 21h6l2.5-7.5m-5.5 1V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
