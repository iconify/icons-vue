<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exzmrnjng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:celestial-navigation" /></template>
<style>
.exzmrnjng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 4l1.5 3.25l3.25 1.5l-3.25 1.5L12 13.5l-1.5-3.25l-3.25-1.5l3.25-1.5ZM2.5 16.25h19m-15.5 3q6 3.75 12 0");
}

</style>
