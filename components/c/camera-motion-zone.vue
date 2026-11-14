<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2r71mb8b"/><path class="a7q0_-bje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-motion-zone" /></template>
<style>
.a7q0_-bje {
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n2r71mb8b {
  d: path("M3.5 8V5.5a2 2 0 0 1 2-2H8m8 0h2.5a2 2 0 0 1 2 2V8m0 8v2.5a2 2 0 0 1-2 2H16m-8 0H5.5a2 2 0 0 1-2-2V16M7 10a1.5 1.5 0 0 1 1.5-1.5H10L11 7h2l1 1.5h1.5A1.5 1.5 0 0 1 17 10v6a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 16Z");
}

</style>
