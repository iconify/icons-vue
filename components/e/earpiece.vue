<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="so9-7foge"/><path class="kdt_a05iy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earpiece" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdt_a05iy {
  d: path("M10.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M11 12l-5.5 4");
}

.so9-7foge {
  d: path("M6.5 9a6.5 6.5 0 0 1 13 0c0 3.5-3 4.5-3.5 7.5A4 4 0 0 1 8.5 18");
}

</style>
