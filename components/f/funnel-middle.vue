<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tffradcsh"/><path class="bsjrnvjup"/><path class="hnebgabqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:funnel-middle" /></template>
<style>
.bsjrnvjup {
  fill: currentColor;
  d: path("M7.5 10.25h9L13.75 14h-3.5Z");
}

.hnebgabqn {
  d: path("M10.25 16.75h3.5v4.5h-3.5Z");
}

.tffradcsh {
  d: path("M2.5 3.5h19l-3 4h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
