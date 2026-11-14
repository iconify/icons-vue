<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5q__b4qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-clubs-crossed" /></template>
<style>
.u5q__b4qr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 2.5l11.25 15m0 0c2.75-1 6.25 0 6.25 2c0 1.5-2 2-4 2H16c-1 0-1.25-1-1-1.75ZM20 2.5l-11.25 15m0 0c-2.75-1-6.25 0-6.25 2c0 1.5 2 2 4 2H8c1 0 1.25-1 1-1.75Z");
}

</style>
