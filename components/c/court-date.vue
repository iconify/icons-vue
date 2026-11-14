<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zm3bz8b7f"/><path class="o57lg88cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:court-date" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o57lg88cg {
  d: path("M14 8.525L16.475 11a1.75 1.75 0 0 1 0 2.475a1.75 1.75 0 0 1-2.475 0L11.525 11a1.75 1.75 0 0 1 0-2.475a1.75 1.75 0 0 1 2.475 0m-1.25 3.725L7 18");
}

.zm3bz8b7f {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-10A3.5 3.5 0 0 1 6.5 4M8 2.5v4m8-4v4");
}

</style>
