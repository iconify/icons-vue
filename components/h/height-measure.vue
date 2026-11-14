<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fppl-nb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:height-measure" /></template>
<style>
.fppl-nb6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.5h1A1.75 1.75 0 0 1 8.5 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 4 19.75V4.25A1.75 1.75 0 0 1 5.75 2.5M4 6h2M4 9.5h1.5M4 13h2m-2 3.5h1.5m4.25-8.25h8.5A1.25 1.25 0 0 1 19.5 9.5a1.25 1.25 0 0 1-1.25 1.25h-8.5A1.25 1.25 0 0 1 8.5 9.5a1.25 1.25 0 0 1 1.25-1.25M2.5 21.5h19");
}

</style>
