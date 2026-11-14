<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jazlf4bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:approach-shoe" /></template>
<style>
.jazlf4bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17.5v-11h5c1 2.5 3.5 3.5 6 4l4.5 1a2.5 2.5 0 0 1 2.5 2.5v3.5Zm0-3h18M10.75 8.75l1.5-2m1.5 3.25l1.5-2");
}

</style>
