<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrngu64ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dao" /></template>
<style>
.lrngu64ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.663 20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.001 0 1.906.16 2.69.481M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM16 4.5a3.5 3.5 0 0 1 .906 6.881M14.5 17.5h7v4h-7Zm2.5 0l-1-3l3-.75l1 3.75");
}

</style>
