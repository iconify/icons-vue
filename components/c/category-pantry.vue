<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbssg_bzl"/><path class="wq7gtcbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-pantry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbssg_bzl {
  d: path("M6.25 2.5h9a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 4.75 4a1.5 1.5 0 0 1 1.5-1.5m-.5 3V19q0 2.5 2.5 2.5h5q2.5 0 2.5-2.5V5.5");
}

.wq7gtcbjx {
  d: path("M16.75 4h2.5v5h-3.5m-8 3h6m-5.5 3.5h.01m4.99 0h.01M10.75 19h.01");
}

</style>
