<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ou4cdl1da"/><path class="ld5qijbpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:format-painter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld5qijbpw {
  d: path("M16.5 6H19a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-6a1 1 0 0 0-1 1v1.5m0 0za1.5 1.5 0 0 1 1.5 1.5v3.5A1.5 1.5 0 0 1 12 21a1.5 1.5 0 0 1-1.5-1.5V16a1.5 1.5 0 0 1 1.5-1.5");
}

.ou4cdl1da {
  d: path("M6.125 3h7.75A2.625 2.625 0 0 1 16.5 5.625v.75A2.625 2.625 0 0 1 13.875 9h-7.75A2.625 2.625 0 0 1 3.5 6.375v-.75A2.625 2.625 0 0 1 6.125 3");
}

</style>
