<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhk-d9b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:density-altitude" /></template>
<style>
.mhk-d9b-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 19.5l6-14l6 14ZM19 4.5v15M16.75 6.75L19 4.5l2.25 2.25m-4.5 10.5L19 19.5l2.25-2.25");
}

</style>
