<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3x_-1mft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jar-mug" /></template>
<style>
.g3x_-1mft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3h7.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.75 7h-7.5A1.75 1.75 0 0 1 4.5 5.25v-.5A1.75 1.75 0 0 1 6.25 3M7.5 7h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 4 18v-7.5A3.5 3.5 0 0 1 7.5 7m8.5 3h1.5a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H16m-9-7.5V17");
}

</style>
