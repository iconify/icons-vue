<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6kxskbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clause-library" /></template>
<style>
.bt6kxskbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9h14.5A1.75 1.75 0 0 1 21 10.75a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 10.75A1.75 1.75 0 0 1 4.75 9m-.25 3.5v7a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-7M4.75 9V5h3v4m2.75 0V3h3v6m2.75 0V4.5h3V9M10 16.5h4");
}

</style>
