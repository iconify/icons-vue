<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7w5jjx3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-coiled" /></template>
<style>
.c7w5jjx3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za2 2 0 0 1 2 2V5a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-.5a2 2 0 0 1 2-2M11.25 7h1.5A2.25 2.25 0 0 1 15 9.25a2.25 2.25 0 0 1-2.25 2.25h-1.5A2.25 2.25 0 0 1 9 9.25A2.25 2.25 0 0 1 11.25 7m.75 4.5l3.5 1.5l-7 2l7 2l-7 2l3.5 1.5v1");
}

</style>
