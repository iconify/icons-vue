<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgc-y6b1f"/><path class="u_kudcbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:height-limit-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_kudcbtr {
  d: path("M9.75 7.75L12 5.5l2.25 2.25m-4.5 4.5L12 14.5l2.25-2.25");
}

.xgc-y6b1f {
  d: path("M8.375 2.5h7.25A4.375 4.375 0 0 1 20 6.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 13.125v-6.25A4.375 4.375 0 0 1 8.375 2.5M12 17.5v4m0-16v9");
}

</style>
