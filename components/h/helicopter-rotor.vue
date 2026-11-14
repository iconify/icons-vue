<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyxxtky5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helicopter-rotor" /></template>
<style>
.hyxxtky5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 14.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-2v-7.5m1.732 10.5L20.227 19m-9.959-3.75L3.773 19");
}

</style>
