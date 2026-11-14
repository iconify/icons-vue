<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t8l--ubbv"/><path class="p5l9nffap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-night" /></template>
<style>
.p5l9nffap {
  d: path("M15.5 15.5v4a3 1.5 0 0 0 6 0v-4");
}

.t8l--ubbv {
  d: path("M19.25 7.75a8.5 8.5 0 1 0-11.5 11.5a9.5 9.5 0 0 1 11.5-11.5ZM15.5 15.5a3 1.5 0 1 0 6 0a3 1.5 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
