<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp-dcka1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bath-tub-clawfoot" /></template>
<style>
.xp-dcka1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h18c0 5-3 8-7 8h-4c-4 0-7-3-7-8Zm4 7l-1.5 4.5M17 16l1.5 4.5M17 9V5.5a2 2 0 0 0-4 0V6");
}

</style>
