<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t79v0nb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bar-stool-high" /></template>
<style>
.t79v0nb1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 3h7.5A1.25 1.25 0 0 1 17 4.25a1.25 1.25 0 0 1-1.25 1.25h-7.5A1.25 1.25 0 0 1 7 4.25A1.25 1.25 0 0 1 8.25 3m.25 2.5L6.5 21m9-15.5l2 15.5M7.25 15h9.5");
}

</style>
