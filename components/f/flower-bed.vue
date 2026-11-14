<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r41nvzbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-bed" /></template>
<style>
.r41nvzbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C5 16 19 16 21.5 20.5M10 4l1 1.25L12 4l1 1.25L14 4v2a2 2 0 0 1-4 0Zm2 4v9.25M3.5 10.5l1 1.25l1-1.25l1 1.25l1-1.25v2a2 2 0 0 1-4 0Zm2 4V18m11-10l1 1.25l1-1.25l1 1.25l1-1.25v2a2 2 0 0 1-4 0Zm2 4v6M12 15.5c0-1.75 1.5-2.5 3-2.5c0 1.75-1.25 2.5-3 2.5Z");
}

</style>
