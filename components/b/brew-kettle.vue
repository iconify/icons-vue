<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpr-eqbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brew-kettle" /></template>
<style>
.mpr-eqbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h14v7a4 4 0 0 1-4 4h-6a4 4 0 0 1-4-4Zm1.5 0a5.5 4 0 0 1 11 0M13 4V2.5M10 19l-1 2.5m4-2.5v2.5m3-2.5l1 2.5M6 15H3.5v2");
}

</style>
