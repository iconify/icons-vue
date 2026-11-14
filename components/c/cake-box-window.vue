<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qaq28qbfw"/><path class="clm01dmtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cake-box-window" /></template>
<style>
.clm01dmtd {
  d: path("M3 12q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0q1.5 2.5 3 0M3 16.25h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qaq28qbfw {
  d: path("m3 9l16.5-5L21 9v10.5H3Zm0 0h18");
}

</style>
