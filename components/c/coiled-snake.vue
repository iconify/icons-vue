<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3d6-pylv"/><path class="p8q7x4b0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coiled-snake" /></template>
<style>
.b3d6-pylv {
  d: path("M19 20.5H6a1.5 1.5 0 0 1 0-3h11a1.5 1.5 0 0 0 0-3H9c-4 0-3-9 1.75-9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8q7x4b0c {
  d: path("M10.75 5.5a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0m5 0h2.75");
}

</style>
