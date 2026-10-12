<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvl3qbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:castanets" /></template>
<style>
.blvl3qbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h7.5A3.75 4.5 0 0 1 3 14m10.5 0H21a3.75 4.5 0 0 1-7.5 0M8 14l4-5m4 5l-4-5m0 0a2 2 0 1 1 0-4a2 2 0 1 1 0 4");
}

</style>
