<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6fdxjj8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-down-left" /></template>
<style>
.h6fdxjj8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.75 4.25v8a2.5 2.5 0 0 1-2.5 2.5H4.75M8.5 11l-3.75 3.75L8.5 18.5");
}

</style>
