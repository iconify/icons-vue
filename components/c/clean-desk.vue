<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w266ljjvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clean-desk" /></template>
<style>
.w266ljjvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h14.5v10H3Zm-.5 13.5H14m4.5-1.75Q19 17.5 21.75 18q-2.75.5-3.25 3.25Q18 18.5 15.25 18q2.75-.5 3.25-3.25Z");
}

</style>
