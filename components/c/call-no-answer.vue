<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lni3pybda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-no-answer" /></template>
<style>
.lni3pybda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.493 13.582C5.395 12.013 4.503 10.175 3.75 8C3.25 6.5 4 5 5.5 4.5l3-1l2 4.5l-2 2c.159.318.356.648.582.983m3.97 3.959c.323.216.642.405.948.558l2-2l4.5 2l-1 3c-.5 1.5-2 2.25-3.5 1.75c-2.147-.743-3.967-1.623-5.523-2.702M20.5 3.5l-17 17");
}

</style>
