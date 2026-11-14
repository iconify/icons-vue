<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qi32jbc4r"/><path class="y1u9pf9uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:geneticist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qi32jbc4r {
  d: path("M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3.5 21c0-4 3.25-6.5 7.5-6.5q.873 0 1.682.138M15.5 15c0 3.25 5 3.25 5 6.5");
}

.y1u9pf9uw {
  d: path("M20.5 15c0 3.25-5 3.25-5 6.5m.25-5.5h4.5m-4.5 4.5h4.5");
}

</style>
