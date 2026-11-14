<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s89f0rlax"/><path class="sgy51dban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-inquiry" /></template>
<style>
.s89f0rlax {
  d: path("M13.3 19H2.5V5h19v7.9");
}

.sgy51dban {
  d: path("M3.5 6.25L12 12.5l8.5-6.25m-4.5 10a2 2 0 1 1 3.25 1.5c-.75.5-1.25 1-1.25 1.5m0 2.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
