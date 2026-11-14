<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hjpx8jbnb"/><path class="e1l46nbxb"/><path class="lyqyhsbxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earlobe" /></template>
<style>
.e1l46nbxb {
  fill: currentColor;
  d: path("M15.5 16c-.25 3.25-2.25 5-4.5 5c-1.75 0-3-1-3.5-2.5c2.5 0 5.5-.5 8-2.5");
}

.hjpx8jbnb {
  d: path("M6 9.5a6.5 6.5 0 0 1 13 0c0 3.5-3 4.5-3.5 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyqyhsbxk {
  d: path("M9.5 9.5a3 3 0 0 1 6 0c0 1.75-1.75 2.25-2.25 4");
}

</style>
