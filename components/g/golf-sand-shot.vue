<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5i-azbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-sand-shot" /></template>
<style>
.p5i-azbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5c3.5 5 15.5 5 19 0m-13-9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-1.5 6l-2-3m12 3l2-3m-7 4h.01");
}

</style>
