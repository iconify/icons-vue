<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxfj2ebbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inference" /></template>
<style>
.fxfj2ebbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7h3a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 13.5v-3A3.5 3.5 0 0 1 10.5 7m-8 5H7M4.75 9.75L7 12l-2.25 2.25M17 12h4.5m-2.25-2.25L21.5 12l-2.25 2.25M10 4v3m4-3v3m-4 10v3m4-3v3");
}

</style>
