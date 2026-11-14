<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j34c4s9al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-detector" /></template>
<style>
.j34c4s9al {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18m-15 0V5q0 4 6 4t6-4V3.5m-10.5 18q-2-2.25 0-4.5t0-4.5m4.5 9q-2-2.25 0-4.5t0-4.5m4.5 9q-2-2.25 0-4.5t0-4.5");
}

</style>
