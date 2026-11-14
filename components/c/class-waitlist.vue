<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtjr4183e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:class-waitlist" /></template>
<style>
.mtjr4183e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 9M5 6h14M7.5 3h9");
}

</style>
