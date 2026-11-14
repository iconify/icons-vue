<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aro1l3b7b"/><path class="dtl3prb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jet-ski-rescue" /></template>
<style>
.aro1l3b7b {
  d: path("M3 13.5h12l6-3.5l-1-.5h-7C12 7.5 10.5 7 8.5 7H6C5 7 4.5 8 4 9.5Z");
}

.dtl3prb-t {
  d: path("m13 9.5l2-5h2.5m-15 13C4 16 5.75 16 7.25 17.5s3.25 1.5 4.75 0m6-2.5v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
