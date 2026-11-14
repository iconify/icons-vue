<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q-39hfr_j"/><path class="z66zg0cwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bride" /></template>
<style>
.q-39hfr_j {
  d: path("M3 19.5c0-3.25 3.25-5.5 7.5-5.5s7.5 2.25 7.5 5.5c0 .6-.4 1-1 1H4c-.6 0-1-.4-1-1ZM6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z66zg0cwt {
  d: path("M8 3.75c4-2 9-.25 10.5 4.25l2.5 8l-5.25-.5");
}

</style>
