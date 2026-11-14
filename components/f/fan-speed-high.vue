<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvtmnqyeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fan-speed-high" /></template>
<style>
.rvtmnqyeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a3 3 0 0 1 0-5.5A3 3 0 0 1 8 12a3 3 0 0 1 4.75 2.75A3 3 0 0 1 8 12a3 3 0 0 1-4.75 2.75A3 3 0 0 1 8 12Zm6.963-4.875a8.5 8.5 0 0 1 0 9.75m2.578-10.837a11.25 11.25 0 0 1 0 11.924M20.124 5a14 14 0 0 1 0 14");
}

</style>
