<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrd3fybwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-dethatch" /></template>
<style>
.rrd3fybwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14L20 2.5M3.5 14h10m-9 0v4m4-4v4m4-4v4m-10 3h19m-6-3q1.5-2.5 3 0q1.5-2.5 3 0");
}

</style>
