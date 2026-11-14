<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i2xksy3-k"/><path class="ym9shwbus"/><path class="nfxpxwz7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leak-repair" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2xksy3-k {
  d: path("M2.5 5H14a5 5 0 0 1 5 5v11.5");
}

.nfxpxwz7x {
  d: path("M8.25 3.25zA1.25 1.25 0 0 1 9.5 4.5V10a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 7 10V4.5a1.25 1.25 0 0 1 1.25-1.25m0 10.25S6.5 15.75 6.5 17a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5");
}

.ym9shwbus {
  d: path("M2.5 9.5h11a1 1 0 0 1 1 1v11");
}

</style>
