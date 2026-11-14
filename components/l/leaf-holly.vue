<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejso0kr0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-holly" /></template>
<style>
.ejso0kr0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5q1.5 2.5 4.5 3q-1 3 2.5 5.5q-3.5 2-2.5 5.5q-3 0-4.5 3q-1.5-3-4.5-3Q8.5 13 5 11q3.5-2.5 2.5-5.5q3-.5 4.5-3m0 17v2m0-2v-12");
}

</style>
