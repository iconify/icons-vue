<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rf2o4ub-c"/><path class="dyh4jubci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live" /></template>
<style>
.dyh4jubci {
  d: path("M15.889 8.111a5.5 5.5 0 0 1 0 7.778m-7.778 0a5.5 5.5 0 0 1 0-7.778m11.166-2.217a9.5 9.5 0 0 1 0 12.212m-14.554 0a9.5 9.5 0 0 1 0-12.212");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rf2o4ub-c {
  fill: currentColor;
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
