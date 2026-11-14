<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-hkkybcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-food-box" /></template>
<style>
.z-hkkybcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18l-1.5 8.5A1.5 1.5 0 0 1 18 21H6a1.5 1.5 0 0 1-1.5-1.5Zm6-8c-1 1.5 1 3 0 4.5M15 3c-1 1.5 1 3 0 4.5M12 4c-1 1.5 1 3 0 4.5");
}

</style>
