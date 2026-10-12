<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="trnn5yb0t"/><path class="sr_etnb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:french-fries-sharp" /></template>
<style>
.sr_etnb3l {
  d: path("m9.5 14.5l2.5 1.667l2.5-1.667");
}

.trnn5yb0t {
  d: path("M5 10.25h14l-1.5 9.25l-.222 1.764l-1.778-.014h-7l-1.778.014L6.5 19.5Zm2.75 0l-.75-5m4 5V3m3 7.25L14.5 4m2.5 6.25l1-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
