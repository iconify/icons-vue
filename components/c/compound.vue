<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ithiembgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compound" /></template>
<style>
.ithiembgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7.75-4l-2 2.25m8.5-2.25l2 2.25");
}

</style>
