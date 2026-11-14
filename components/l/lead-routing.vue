<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dsim5lx0w"/><path class="xv-y5ypoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-routing" /></template>
<style>
.dsim5lx0w {
  d: path("M3.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-1 11.5c0-3.5 1.75-5.5 4-5.5s4 2 4 5.5m3-7.5h3L21 7.5M16.5 12l4.5 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xv-y5ypoc {
  d: path("M17.5 7.5H21V11");
}

</style>
