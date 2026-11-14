<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5298tb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardinal-mark-north" /></template>
<style>
.d5298tb3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l3.75 4.75h-7.5Zm0 4.75L15.75 12h-7.5ZM12 12v1.5m-4 4a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
