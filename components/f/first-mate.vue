<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp5pm1hbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-mate" /></template>
<style>
.mp5pm1hbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5.5c0-2.5 15-2.5 15 0c0 1-2.5 3-3.5 3H8c-1 0-3.5-2-3.5-3m3.5 3v2a4 4 0 0 0 8 0v-2m-11.5 13c0-2.5 3.25-4.25 7.5-4.25s7.5 1.75 7.5 4.25");
}

</style>
