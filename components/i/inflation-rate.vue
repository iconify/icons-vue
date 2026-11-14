<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrxcd3j_x"/><path class="ivfjl_kqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inflation-rate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivfjl_kqp {
  d: path("M5.5 10.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 21V3m-3 3l3-3l3 3");
}

.wrxcd3j_x {
  d: path("m3.174 7.751l1.875-2.083a2.625 2.625 0 0 1 3.902 0l1.875 2.083a2.63 2.63 0 0 1 .674 1.756v8.868A2.625 2.625 0 0 1 8.875 21h-3.75A2.625 2.625 0 0 1 2.5 18.375V9.507a2.63 2.63 0 0 1 .674-1.756");
}

</style>
