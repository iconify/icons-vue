<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ylnr1s7om"/><path class="was_9yb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-wedding" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.was_9yb3e {
  d: path("M10 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ylnr1s7om {
  d: path("M4 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
