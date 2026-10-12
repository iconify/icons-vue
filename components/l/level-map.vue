<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="u978tybzz"/><circle class="xk-oew7zv"/><path class="hv18zsmuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:level-map" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv18zsmuk {
  d: path("m6.8 17.4l2.4-1.8m3.81-2.36L17.5 11V7.75m0-5h3.75l-1 2.5l1 2.5H17.5Z");
}

.u978tybzz {
  cx: 5px;
  cy: 18.75px;
  r: 2.25px;
}

.xk-oew7zv {
  cx: 11px;
  cy: 14.25px;
  r: 2.25px;
}

</style>
