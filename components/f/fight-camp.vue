<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blhgrybek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fight-camp" /></template>
<style>
.blhgrybek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.249 20.5H2.5L10 4l4.086 8.99M10 4V2.5m0 9.5v8.5m6-4.75h6v5.75h-6ZM16 18h6m-4.25-3.25v1.5m2.5-1.5v1.5");
}

</style>
