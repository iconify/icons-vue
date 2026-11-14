<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2sqpjbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dumbbell-pair" /></template>
<style>
.e2sqpjbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h3.5V9H3Zm14.5 0H21V9h-3.5Zm-11 2.25h11M3 12h3.5v4.5H3Zm14.5 0H21v4.5h-3.5Zm-11 2.25h11M2.5 20h19");
}

</style>
