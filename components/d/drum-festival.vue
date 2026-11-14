<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3_tmg2ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drum-festival" /></template>
<style>
.r3_tmg2ej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11c0 3.5 4.5 4.5 4.5 6.5l-1.5 4h7l-1.5-4c0-2 4.5-3 4.5-6.5m-14 0h15M5 2.5L14.5 8M19 2.5L9.5 8");
}

</style>
