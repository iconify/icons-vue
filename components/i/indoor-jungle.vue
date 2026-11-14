<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0va9tb5h"/><path class="mxd2nn09i"/><path class="wk5m6d7sw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:indoor-jungle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxd2nn09i {
  d: path("M11.83 16h2.34a1.5 1.5 0 0 1 1.471 1.794l-.4 2A1.5 1.5 0 0 1 13.77 21h-1.54a1.5 1.5 0 0 1-1.471-1.206l-.4-2A1.5 1.5 0 0 1 11.83 16");
}

.n0va9tb5h {
  d: path("M3 3v18h18.5");
}

.wk5m6d7sw {
  d: path("M13 16c-3-1-6.5-4-7-8c3.5.5 6.5 3.5 7 8m0 0c-2-4-1.5-9 0-12c1.5 3 2 8 0 12m0 0c3-1 6.5-4 7-8c-3.5.5-6.5 3.5-7 8");
}

</style>
