<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxqjc8bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-pan" /></template>
<style>
.gxqjc8bdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h12v8.5h-12Zm12 3l5-2.25v7l-5-2.25Zm-6 5.5v4m-4 4l4-4l4 4m4.5-3.75l-1.75 1.75L17 20.25m-1.75-1.75h6.5M20 16.75l1.75 1.75L20 20.25");
}

</style>
