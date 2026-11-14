<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz5682b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:attach" /></template>
<style>
.iz5682b6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 11.5L12.5 18a4.25 4.25 0 0 1-6-6l7-7a2.83 2.83 0 0 1 4 4L11 15.5a1.42 1.42 0 0 1-2-2l6-6");
}

</style>
