<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xrnml6bdw"/><path class="o783q5dsu"/><path class="wzpcx1iac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flat-track-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o783q5dsu {
  d: path("M4 10h4.5l2-2H16l-3 5H9.5L6 16.5Z");
}

.wzpcx1iac {
  d: path("M13.5 5.5h2l2.5 11");
}

.xrnml6bdw {
  d: path("M2.5 16.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
