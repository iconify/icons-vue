<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhj6pzbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-filter" /></template>
<style>
.nhj6pzbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5L6 4.25q.25-1 1.5-1h5q1.25 0 1.5 1l1.5 4.25m-4 6h-9v-6h15v4.7m-12 1.3V17M16 16h5.5l-2 2.75v2.75l-1.5-1v-1.75Z");
}

</style>
