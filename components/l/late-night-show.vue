<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c19vlx85y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:late-night-show" /></template>
<style>
.c19vlx85y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19m-18 0q5 5 0 17.5M20.5 3q-5 5 0 17.5m-18 0h19M13 8a3.5 3.5 0 1 0 2.25 6A2.75 2.75 0 0 1 13 8Z");
}

</style>
