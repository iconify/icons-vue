<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ysl3vc4lj"/><path class="fgp1rfbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:async-await" /></template>
<style>
.fgp1rfbli {
  d: path("m12.5 13l1.5-1.5l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysl3vc4lj {
  d: path("M3 3h10l-5 9Zm5 9l5 9H3Zm9.5-3.5A3.5 3.5 0 1 1 14 12");
}

</style>
