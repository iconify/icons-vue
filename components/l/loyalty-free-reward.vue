<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8-464brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loyalty-free-reward" /></template>
<style>
.y8-464brm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h17v11h-17Zm-1-3.5h19V10h-19Zm9.5 0V21m0-14.5C12 3 8 3 8.5 5C9 6.5 12 6.5 12 6.5m0 0C12 3 16 3 15.5 5C15 6.5 12 6.5 12 6.5");
}

</style>
