<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5jlglb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bikini" /></template>
<style>
.t5jlglb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5L8 4l4 6.5L16 4l4 6.5m-17.5 0h19m-19 3h19M5 13.5C7 16 9 19 10 20h4c1-1 3-4 5-6.5");
}

</style>
