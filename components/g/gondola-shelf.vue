<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baccrqbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gondola-shelf" /></template>
<style>
.baccrqbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H7v19H2.5ZM7 19h14.5v2.5H7ZM7 4h14.5M7 10h14.5M7 15.5h14.5M9 6.5h3V10H9Zm5.5 0h3V10h-3Zm-5.5 6h4v3H9Zm7-.5h3v3.5h-3Z");
}

</style>
