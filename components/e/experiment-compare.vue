<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6zy9e1wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:experiment-compare" /></template>
<style>
.x6zy9e1wz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h3v6l2.5 12h-8L5 9Zm10.75 0h3v6l2.5 12h-8l2.5-12Zm-12 12h5.5m5.25 0H20");
}

</style>
