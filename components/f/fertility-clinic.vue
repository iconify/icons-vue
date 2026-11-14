<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmghfgb8t"/><path class="ivpfpjbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fertility-clinic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivpfpjbaw {
  d: path("M6 21.5V16h4v5.5m8.75 0V15m0 1.5c-2.25 0-2.5-2-2.5-3.5c1.75 0 2.5 1.5 2.5 3.5m0-1.5c0-2 1-3.5 3-3.5c0 2-1 3.5-3 3.5");
}

.pmghfgb8t {
  d: path("M5.125 2.5h5.75A2.625 2.625 0 0 1 13.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5M8 6v5M5.5 8.5h5");
}

</style>
