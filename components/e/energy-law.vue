<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-evo6b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-law" /></template>
<style>
.b-evo6b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5h13m-6.5-3v17m-2.5 0h5m1-7l3-7l3 7Zm0 0a3 3 0 0 0 6 0M6.456 8.275l1.714 3.184A1.045 1.045 0 0 1 7.25 13a1.366 1.366 0 0 0-1.326 1.698L6.25 16a.376.376 0 0 1-.697.267l-2.234-4.22A1.054 1.054 0 0 1 4.25 10.5h.051a1.5 1.5 0 0 0 1.488-1.686L5.75 8.5a.377.377 0 0 1 .706-.225");
}

</style>
