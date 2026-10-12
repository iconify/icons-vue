<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hts6s58pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:femur-bone" /></template>
<style>
.hts6s58pg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 16.79V10l-.66-2.41a2.25 2.25 0 1 1 .36-2.71L13 4.25a1.25 1.25 0 0 1 1.25 1.5l-1 3v8.04a2.1 2.1 0 1 1-1.25 2.6a2.1 2.1 0 1 1-1.25-2.6");
}

</style>
