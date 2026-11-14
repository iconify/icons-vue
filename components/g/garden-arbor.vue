<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3m2m23cu"/><path class="gt0gm1b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-arbor" /></template>
<style>
.gt0gm1b8d {
  d: path("M6 13.5c2.5 0 3.5-1.5 3.5-3.5C7 10 6 11.5 6 13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3m2m23cu {
  d: path("M6 20.5V10a6 6 0 0 1 12 0v10.5M3.5 7h17m-18 13.5h19M6 17c-2.5 0-3.5-1.5-3.5-3.5C5 13.5 6 15 6 17");
}

</style>
