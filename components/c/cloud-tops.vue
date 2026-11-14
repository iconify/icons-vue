<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzu8avb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-tops" /></template>
<style>
.pzu8avb0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21h13a2.75 2.75 0 0 0 .5-5.5a4 4 0 0 0-7.5-1.5A3.5 3.5 0 0 0 5 15.75A2.75 2.75 0 0 0 5.5 21m3-8.75V3M6 5.5L8.5 3L11 5.5M5.5 3h6");
}

</style>
