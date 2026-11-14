<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7a4ajmmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-row-letter" /></template>
<style>
.a7a4ajmmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16v-4.25a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3V16M7 16h10a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 17 19H7a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 7 16m-4.25-4v9.5m18.5-9.5v9.5M10 6V2.5h5.5l-1.75 1.75L15.5 6Z");
}

</style>
