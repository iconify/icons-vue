<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jisu4559b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funeral-urn" /></template>
<style>
.jisu4559b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5h11m-9 0q3.5-5 7 0m-8 0C3 10 3.5 17.5 9 18h6c5.5-.5 6-8 1.5-10.5M10 18l-1 3.5h6L14 18");
}

</style>
