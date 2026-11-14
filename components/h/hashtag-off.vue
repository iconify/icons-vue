<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exftf0bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hashtag-off" /></template>
<style>
.exftf0bcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4v1.1m0 7.8V20m6-16v7.1m0 7.8V20M4 9h1.1m7.8 0H20M4 15h7.1m7.8 0H20M3.5 3.5l17 17");
}

</style>
