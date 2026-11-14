<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he1xyqbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-elevator" /></template>
<style>
.he1xyqbac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.005 13.995za1.75 1.75 0 0 1 0 2.475L6.47 20.005a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l3.535-3.535a1.75 1.75 0 0 1 2.475 0M10 14l4.5-4.5m0 0c1-3 3-6 6-6.75c.5 3-2.5 5.75-6 6.75");
}

</style>
