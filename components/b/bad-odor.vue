<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxktzacxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bad-odor" /></template>
<style>
.zxktzacxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14a4 4 0 0 1 0-8a4.75 4.75 0 0 1 9 .5A3.75 3.75 0 0 1 17 14ZM8 16.75C6.75 18 9.25 19.5 8 21.5m4-4.75c-1.25 1.25 1.25 2.75 0 4.75m4-4.75c-1.25 1.25 1.25 2.75 0 4.75");
}

</style>
