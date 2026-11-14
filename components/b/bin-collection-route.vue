<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ug61ms40t"/><path class="q4ris7c2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-collection-route" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4ris7c2o {
  d: path("M4.5 7v7.5a4 4 0 0 0 4 4H11");
}

.ug61ms40t {
  d: path("M12 9.5h9.5m-8.5 0l1 11h5.5l1-11m-5.25-2.75h3M2.5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
