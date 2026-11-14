<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rs_t11bjv"/><path class="zg7snibqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hikers-only" /></template>
<style>
.rs_t11bjv {
  d: path("M3.5 10.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0ZM12 19v2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zg7snibqu {
  d: path("M11.75 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm.5 3.25l-.75 3M9.25 15l2.25-2.75L13.75 15M9.5 11.25l2.5-1l2.25 1.5");
}

</style>
