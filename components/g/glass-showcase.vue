<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmj6nob3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glass-showcase" /></template>
<style>
.fmj6nob3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h15v17h-15Zm2 17v2m11-2v2M4.5 8.25h15m-15 5.5h15m-5.5 3.5l2.5-1.5M13.25 6l2.5-1.5");
}

</style>
