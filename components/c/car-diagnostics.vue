<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x2wek2hyr"/><path class="fx64rflxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-diagnostics" /></template>
<style>
.fx64rflxz {
  d: path("M8.5 10h.011a1.5 1.5 0 0 0 1.379-.909l.36-.841a.677.677 0 0 1 1.273.081l.954 3.338a.677.677 0 0 0 1.273.081l.36-.841A1.5 1.5 0 0 1 15.489 10h.011zm3.5 7.5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2wek2hyr {
  d: path("M4.5 5A2.5 2.5 0 0 1 7 2.5h10A2.5 2.5 0 0 1 19.5 5v8L16 17.5H8L4.5 13Z");
}

</style>
