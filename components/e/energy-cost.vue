<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fq4mjcbko"/><path class="to_-cu-0k"/><path class="s7ybhwfgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-cost" /></template>
<style>
.fq4mjcbko {
  d: path("M2.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.s7ybhwfgn {
  d: path("m12.25 6.5l-5 6.25h3.5l-1 4.75l5-6.25h-3.5Z");
}

.to_-cu-0k {
  d: path("M11 3.5h2a8.5 8.5 0 0 1 0 17h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
