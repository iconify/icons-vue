<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8x-git8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flu-shot" /></template>
<style>
.a8x-git8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.005 8.434l1.061 1.061a1.75 1.75 0 0 1 0 2.475L9.47 16.566a1.75 1.75 0 0 1-2.475 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.475l4.596-4.596a1.75 1.75 0 0 1 2.475 0M13.5 9l4-4m-11 11l-2.25 2.25m-1.5-1.5l3 3M20 7.5s2 2.25 2 3.5a2 2 0 0 1-4 0c0-1.25 2-3.5 2-3.5");
}

</style>
