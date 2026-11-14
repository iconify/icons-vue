<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6bi054kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:applause-sign" /></template>
<style>
.c6bi054kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 21.5l-2-5.5c-.5-1.5 1-2.5 2-1.5l1 1V10c0-1.25 1.25-2.25 2.5-2s2 1.25 2 2.5c0-1.25.75-2.25 2-2.5s2.5.75 2.5 2v5.5l1-1c1-1 2.5 0 2 1.5l-2 5.5m-5.5-11v11M5.5 4L7 5.5m5-3v3M18.5 4L17 5.5");
}

</style>
