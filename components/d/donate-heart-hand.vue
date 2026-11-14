<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvwot9qde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-heart-hand" /></template>
<style>
.gvwot9qde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h4l3.5 2.5h5l4-3a1.75 1.75 0 0 1 2.25 2.75L16.5 21h-14Zm9.5-1.5L7.5 8A3 3 0 0 1 12 4.25A3 3 0 0 1 16.5 8ZM5.5 14v7");
}

</style>
