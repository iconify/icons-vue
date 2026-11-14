<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vyx_n_b5e"/><path class="x8etu9bhl"/><path class="z87sto2xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-pass-day" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyx_n_b5e {
  d: path("M6.5 3.5h6A3.5 3.5 0 0 1 16 7v6a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 3 13V7a3.5 3.5 0 0 1 3.5-3.5M7 2v3m5-3v3");
}

.x8etu9bhl {
  fill: currentColor;
  d: path("M7.5 9.5zA1.5 1.5 0 0 1 9 11a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 6 11a1.5 1.5 0 0 1 1.5-1.5");
}

.z87sto2xh {
  d: path("M15.75 19v2m2.75-4v4m2.75-6v6");
}

</style>
