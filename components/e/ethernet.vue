<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_mdodvyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ethernet" /></template>
<style>
.o_mdodvyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 4.5h10.75A2.625 2.625 0 0 1 20 7.125v7.125A1.75 1.75 0 0 1 18.25 16a1.75 1.75 0 0 0-1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 0 5.75 16A1.75 1.75 0 0 1 4 14.25V7.125A2.625 2.625 0 0 1 6.625 4.5M8 8v2m2.75-2v2m2.5-2v2M16 8v2");
}

</style>
