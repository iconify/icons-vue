<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtt69o3nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crowd-flow" /></template>
<style>
.qtt69o3nb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-3 11.5C5.5 16 8 14 11 14c1.305 0 2.515.378 3.466 1.094M2.25 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm13.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM6 10c-2.25 0-3.5 1.5-3.5 3.5M16 10c1.895 0 3.081 1.064 3.408 2.595M15 18.5h6.5m-4.5-2l-2 2l2 2m2.5-4l2 2l-2 2");
}

</style>
