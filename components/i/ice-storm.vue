<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3z_yibuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-storm" /></template>
<style>
.h3z_yibuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14.5a3.5 3.5 0 0 1 0-7a5 5 0 0 1 9.5-.5a3.75 3.75 0 0 1 0 7.5Zm.5 0l1 4.5l1-4.5m1.75 0l1 6l1-6m1.75 0l1 4.5l1-4.5");
}

</style>
