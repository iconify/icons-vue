<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgnqjrbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arcade-arches" /></template>
<style>
.cgnqjrbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18.5v-10a3 3 0 0 1 6 0a3 3 0 0 1 6 0a3 3 0 0 1 6 0v10M9 8.5v10m6-10v10m-12.5 0h19");
}

</style>
