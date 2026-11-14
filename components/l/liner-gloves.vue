<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9tlwybdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liner-gloves" /></template>
<style>
.i9tlwybdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 21.5v-6L5.5 12.25a1.25 1.25 0 0 1 1.75-1.75l1.5 1.5V5.5a1.25 1.25 0 0 1 2.5 0V10V3.75a1.25 1.25 0 0 1 2.5 0V10V4.5a1.25 1.25 0 0 1 2.5 0V10V7a1.25 1.25 0 0 1 2.5 0v7.5l-1 3v4Zm0-3.5h9");
}

</style>
