<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="janwq29et"/><path class="a2gp2ek2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lava-flow" /></template>
<style>
.a2gp2ek2z {
  d: path("M10.5 8c0 3.5-2 4.5-2 7.5c0 2.5-2 3.5-2.5 5h12c-.5-1.5-2.5-2.5-2.5-5c0-3-2-4-2-7.5M9 5a1.5 1.5 0 0 1 3-1a1.5 1.5 0 0 1 3 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.janwq29et {
  d: path("M2.5 20.5L9 8h6l6.5 12.5");
}

</style>
