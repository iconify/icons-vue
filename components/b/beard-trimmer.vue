<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1sasjb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beard-trimmer" /></template>
<style>
.v1sasjb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5.5h11V9h-11ZM8 9v10a2.5 2.5 0 0 0 2.5 2.5h3A2.5 2.5 0 0 0 16 19V9M8.5 2.5v3m3.5-3v3m3.5-3v3");
}

</style>
