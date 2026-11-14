<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg9sz8lca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-putt" /></template>
<style>
.bg9sz8lca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 18.5a5.5 2.5 0 1 0 11 0a5.5 2.5 0 1 0-11 0ZM3.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm9.75.5Q15.5 9 15.5 13");
}

</style>
