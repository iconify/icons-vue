<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c71l81bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:halftone" /></template>
<style>
.c71l81bgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8 0h.01M4 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12 0h.01M6.5 21.5h.01");
}

</style>
