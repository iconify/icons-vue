<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-tm_4bwd"/><circle class="f36rksbvd"/><circle class="b0vv8ac2d"/><circle class="lpfy_mbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carbon-footprint" /></template>
<style>
.b0vv8ac2d {
  cx: 10.25px;
  cy: 4px;
  r: 1.25px;
}

.f36rksbvd {
  cx: 15.25px;
  cy: 5px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpfy_mbzj {
  cx: 6px;
  cy: 6.5px;
  r: 1.25px;
}

.m-tm_4bwd {
  d: path("M7 12c0-2.5 1.75-3.75 4.5-3.75S16 9.5 16 12c0 2.75-1.5 4-1.5 6.5a2.75 2.75 0 0 1-5.5 0c0-2.25-2-3.75-2-6.5");
}

</style>
