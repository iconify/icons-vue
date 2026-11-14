<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6n6noo0n"/><path class="xeen6pbkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drop-heart" /></template>
<style>
.l6n6noo0n {
  d: path("M12 2.5s7 7.5 7 12a7 7 0 0 1-14 0c0-4.5 7-12 7-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xeen6pbkr {
  fill: currentColor;
  d: path("M12 18.25L9.25 15.5A1.75 1.75 0 0 1 12 13a1.75 1.75 0 0 1 2.75 2.5Z");
}

</style>
