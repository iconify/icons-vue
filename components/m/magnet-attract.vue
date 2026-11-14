<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijrurrbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnet-attract" /></template>
<style>
.ijrurrbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8.75H8a5.5 5.5 0 0 0 0 11h2.5v-3H8a2.5 2.5 0 0 1 0-5h2.5Zm-2.5 0v3m0 5v3m5.5-11H16a5.5 5.5 0 0 1 0 11h-2.5v-3H16a2.5 2.5 0 0 0 0-5h-2.5Zm2.5 0v3m0 5v3M3.5 4.5h6M8 3l1.5 1.5L8 6m12.5-1.5h-6M16 3l-1.5 1.5L16 6");
}

</style>
