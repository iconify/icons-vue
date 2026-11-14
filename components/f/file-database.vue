<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="r3fo88abs"/><path class="ymcueen-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-database" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3fo88abs {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-11 3.25C8.5 10.8 10.1 10 12 10s3.5.8 3.5 1.75v5.5c0 .95-1.6 1.75-3.5 1.75s-3.5-.8-3.5-1.75Z");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.ymcueen-y {
  d: path("M8.5 11.75c0 .95 1.6 1.75 3.5 1.75s3.5-.8 3.5-1.75");
}

</style>
