<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7gzi433p"/><path class="ltti1pb2d"/><circle class="apaf5vfgj"/><path class="mzd__mbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flamingo" /></template>
<style>
.apaf5vfgj {
  cx: 8.5px;
  cy: 4.5px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltti1pb2d {
  d: path("M9.75 10.25c-2.75-1-3.5-3-2.5-4.75");
}

.mzd__mbyi {
  d: path("m10 3.25l2 1c.5.25.6.75.35 1.15L11.25 7l-1.6-2.25Zm4.5 11V21m0-3.25L12 16");
}

.o7gzi433p {
  d: path("M9 11c0-2.5 2.5-4 5.5-4s5.75 1.5 5.75 3.25c0 .5-.5.75-1 .5L16 13.5c-.75.5-1.75.75-2.75.75C10.75 14.25 9 13 9 11");
}

</style>
