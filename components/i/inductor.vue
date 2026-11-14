<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gthgi4uth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inductor" /></template>
<style>
.gthgi4uth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h2m0 0A2.25 3 0 0 1 9 14a2.25 3 0 0 1 4.5 0a2.25 3 0 0 1 4.5 0a2.25 3 0 0 1 4 0");
}

</style>
