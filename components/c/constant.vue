<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzog80b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:constant" /></template>
<style>
.rzog80b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 10h6.5a5.25 5.25 0 0 1 5.25 5.25v1a5.25 5.25 0 0 1-5.25 5.25h-6.5a5.25 5.25 0 0 1-5.25-5.25v-1A5.25 5.25 0 0 1 8.75 10M7.5 10V7a4.5 4.5 0 0 1 9 0v3M9 14.25h6m-6 3h6");
}

</style>
