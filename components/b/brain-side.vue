<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="prkr2ccod"/><path class="vov89fb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brain-side" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prkr2ccod {
  d: path("M13.5 21v-3.5h-6c-3 0-5-2.25-5-5.5c0-4.75 4-8 9-8c5.5 0 10 3.25 10 7.5c0 3.25-2.25 6-5 6V21");
}

.vov89fb0r {
  d: path("M6.5 10.5c2.5-3 4.5 2.5 7 0c1.5-1.5 3-1 4 .5");
}

</style>
