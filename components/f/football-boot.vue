<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3mybkblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:football-boot" /></template>
<style>
.t3mybkblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h6l.5 5c4 .5 8.5 2 10 5V16H3zm8 5.5l.75 2.75m2.5-2l.75 2.75M5.5 16v3m4.5-3v3m4.5-3v3m4.5-3v3");
}

</style>
