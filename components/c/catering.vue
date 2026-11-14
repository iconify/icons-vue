<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4psfbcyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catering" /></template>
<style>
.q4psfbcyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5c0-4 15-4 15 0m-17 0h19l-1.5 4H4Zm1.5 4L3 20m17-9.5l1 9.5m-9-6.5c2.5 2.5 2.5 6 0 6s-2.5-3.5 0-6Z");
}

</style>
