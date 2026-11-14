<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r289t4f3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blender" /></template>
<style>
.r289t4f3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5c0-2.5 10-2.5 10 0Zm0 0h10l-1.5 9h-7Zm-.5 9h11v7.5h-11Zm5.5 3.75h.01");
}

</style>
