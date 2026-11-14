<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmse5m2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boom-arm" /></template>
<style>
.atmse5m2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h15M7 3.5v15M3 20a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0ZM18.5 3.5v4m-2 0h4l1 5h-6Z");
}

</style>
