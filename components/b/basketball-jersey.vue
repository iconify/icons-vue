<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyvbphscw"/><path class="wr3-h-bha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-jersey" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wr3-h-bha {
  d: path("M9 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.xyvbphscw {
  d: path("M7.5 2.5V5C7.5 7.5 5 8 5 10.5v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-10c0-2.5-2.5-3-2.5-5.5V2.5h-2a2.5 2.5 0 0 1-5 0Z");
}

</style>
