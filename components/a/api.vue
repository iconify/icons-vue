<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s70kwdk_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api" /></template>
<style>
.s70kwdk_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7zA2.75 2.75 0 0 1 8 9.75v4.5A2.75 2.75 0 0 1 5.25 17a2.75 2.75 0 0 1-2.75-2.75v-4.5A2.75 2.75 0 0 1 5.25 7m13.5 0za2.75 2.75 0 0 1 2.75 2.75v4.5A2.75 2.75 0 0 1 18.75 17A2.75 2.75 0 0 1 16 14.25v-4.5A2.75 2.75 0 0 1 18.75 7M8 9.5h2.5v5H8m8-5h-2.5v5H16M10.5 12h3");
}

</style>
