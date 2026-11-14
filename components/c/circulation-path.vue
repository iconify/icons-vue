<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uu-y5wjts"/><path class="iv1dksbnm"/><path class="w0pzm1bew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circulation-path" /></template>
<style>
.iv1dksbnm {
  d: path("M14 4.5a11 11 0 0 1-1 3.75M11.75 10A11 11 0 0 1 9 12.75m-2 1a11 11 0 0 1-2.5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uu-y5wjts {
  d: path("M3 12V3.5h8.5m5 0H21v17H3V17");
}

.w0pzm1bew {
  d: path("M6.75 12.25L4.5 14.5l2.25 2.25Z");
}

</style>
