<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfccm134n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:free-samples" /></template>
<style>
.xfccm134n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H15M3.5 4l1.75 15.5h7L14 4m4.75 9Q19 16.25 22 16.5q-3 .25-3.25 3.5q-.25-3.25-3.25-3.5q3-.25 3.25-3.5Z");
}

</style>
