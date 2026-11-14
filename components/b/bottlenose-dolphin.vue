<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7sluyf4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottlenose-dolphin" /></template>
<style>
.o7sluyf4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 15.5c.5-4 2.5-7 5-8.25L11 3.5l2.75 2.75c1.75-.25 3.25 0 4.5 1L20.5 8.5v.75L18 9.5c-4-.5-7.25 1.5-9.25 6.25ZM3 19.25q3-2 6 0t6 0t6 0");
}

</style>
