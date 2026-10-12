<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8e6vmbvg"/><path class="opj8r-4zm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compost-bin" /></template>
<style>
.e8e6vmbvg {
  d: path("M6.25 8.25h11.5q1.5 0 1.36 1.49l-.97 10.02q-.14 1.49-1.64 1.49h-9q-1.5 0-1.64-1.49L4.89 9.74q-.14-1.49 1.36-1.49m-3.5-2.5h18.5m-11.5 0v-2.5h4.5v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opj8r-4zm {
  d: path("M9 18.25c.25-3.5 2-5.5 6-6.25c-.25 3.5-2 5.5-6 6.25");
}

</style>
