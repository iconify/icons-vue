<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4tx0ccaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cyclone-track" /></template>
<style>
.l4tx0ccaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 8a1.5 1.5 0 0 0-3 0a3 3 0 0 0 6 0a4.5 4.5 0 0 0-9 0m-.25 2.75l-.75 2.5m-1.5 2.5L7.25 18M5 19.5l-2.5 1");
}

</style>
