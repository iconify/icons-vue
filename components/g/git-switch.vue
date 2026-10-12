<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kahzru8yh"/><circle class="euy-r2rrr"/><path class="eji-0sbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-switch" /></template>
<style>
.eji-0sbbl {
  d: path("M9 17.75h5.25a3 3 0 0 0 3-3v-5.5m-2.25 2L17.25 9l2.25 2.25");
}

.euy-r2rrr {
  cx: 17.25px;
  cy: 5.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kahzru8yh {
  cx: 6.75px;
  cy: 17.75px;
  r: 2.25px;
}

</style>
