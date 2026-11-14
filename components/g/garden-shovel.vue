<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siqarp2jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-shovel" /></template>
<style>
.siqarp2jf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 7.5L14 5q3-2.5 6.5-1.5Q21.5 7 19 10l-2.5 2.5ZM8 16l6-6m-6 6l-5.25 1.75l3.5 3.5Z");
}

</style>
