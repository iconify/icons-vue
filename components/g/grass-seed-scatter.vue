<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c81u_gb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grass-seed-scatter" /></template>
<style>
.c81u_gb3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21c0-6-1-12 .5-17M10 21c-.5-5-4-9-7-11m7 11c.5-5 3-9 6-11m2-5.5h.01m2.49 5h.01M19.5 15h.01");
}

</style>
