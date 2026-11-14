<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zoej7biec"/><path class="d8e0s9b2b"/><path class="xidmy_bpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-organs" /></template>
<style>
.d8e0s9b2b {
  fill: currentColor;
  d: path("M10 8c0 2-1 3.5-1 5.5c0 2.75 2 4.5 4.5 4s3.25-3 1.75-4.25c-1-.75-2-.25-2.5-1.25s-.25-2.5.25-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xidmy_bpw {
  d: path("M11.5 2.5v5m2.75 9.75c1 1 1 2.25 0 3.25");
}

.zoej7biec {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3");
}

</style>
