<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oxbyo_dfc"/><path class="y4vz85b2k"/><path class="flvhztbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coffee-break-sign" /></template>
<style>
.flvhztbfg {
  d: path("M10.25 10h5v3.25a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5Zm5 1H16a1.75 1.75 0 0 1 0 3.5h-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oxbyo_dfc {
  d: path("M4.5 21.5V3H19m-9 0v3.5M18 3v3.5");
}

.y4vz85b2k {
  d: path("M10.125 6.5h7.75A2.625 2.625 0 0 1 20.5 9.125v6.75a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 7.5 15.875v-6.75A2.625 2.625 0 0 1 10.125 6.5");
}

</style>
