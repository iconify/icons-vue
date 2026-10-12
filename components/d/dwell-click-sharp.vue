<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qs8_p6b1m"/><path class="fmhxclbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dwell-click-sharp" /></template>
<style>
.fmhxclbnm {
  d: path("M6 11.75a4.75 4.75 0 1 1 8.25-4");
}

.qs8_p6b1m {
  d: path("m10.11 8.84l9.53 5.32l.61.34l-.68.17l-3.64.91l-.68.17l-.28.64l-1.69 3.97L13 21l-.19-.67L9.69 9.17L9.5 8.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
