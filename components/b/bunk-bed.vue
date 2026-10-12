<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voh-sybvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bunk-bed" /></template>
<style>
.voh-sybvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3v18M20 3v18M4 9h16M4 16h16M7 9V7.5a1.25 1.25 0 0 1 1.25-1.25h2A1.25 1.25 0 0 1 11.5 7.5V9M7 16v-1.5a1.25 1.25 0 0 1 1.25-1.25h2a1.25 1.25 0 0 1 1.25 1.25V16");
}

</style>
