<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-3u4bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inflammation" /></template>
<style>
.mp-3u4bdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5H6C6 15 8.75 13 12 13s6 2 6 6.5h3.5M5.75 13.25L4.5 12m13.75 1.25L19.5 12M9 9.5c-1-1 1-3 0-4c-.75-.75 0-2 .25-2.5M15 9.5c-1-1 1-3 0-4c-.75-.75 0-2 .25-2.5");
}

</style>
