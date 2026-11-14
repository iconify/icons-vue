<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c7pvsf85o"/><path class="iiqj7f4zj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-gel" /></template>
<style>
.c7pvsf85o {
  d: path("m5.5 3.5l2.25-1l2 1l2.25-1l2.25 1l2-1l2.25 1V20a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 20Zm0 3h13");
}

.iiqj7f4zj {
  d: path("M13.25 9.25L8.5 14.5H12l-1.25 4.25L15.5 13H12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
