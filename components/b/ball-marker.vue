<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnejk-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-marker" /></template>
<style>
.gnejk-byp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 9 8ZM2.5 18.5a6 3 0 1 0 12 0a6 3 0 1 0-12 0Zm6 0h.01");
}

</style>
