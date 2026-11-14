<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uefgusb4a"/><path class="l_nh9c7dc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guitar-body" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_nh9c7dc {
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 4.75h5");
}

.uefgusb4a {
  d: path("M8.75 10.25a4.5 4.5 0 1 1 6.5 0a6 6 0 1 1-6.5 0");
}

</style>
