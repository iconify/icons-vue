<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nctxihvqt"/><path class="x6obu7bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copy-properties" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nctxihvqt {
  d: path("M8 4h8a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V7.5A3.5 3.5 0 0 1 8 4");
}

.x6obu7bok {
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4A1.5 1.5 0 0 1 14 5.5h-4A1.5 1.5 0 0 1 8.5 4A1.5 1.5 0 0 1 10 2.5m3.061 8.561l1.378 1.378a1.5 1.5 0 0 1 0 2.122l-1.378 1.378a1.5 1.5 0 0 1-2.122 0l-1.378-1.378a1.5 1.5 0 0 1 0-2.122l1.378-1.378a1.5 1.5 0 0 1 2.122 0");
}

</style>
