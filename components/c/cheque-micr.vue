<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5606nb6s"/><path class="fe645xucn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-micr" /></template>
<style>
.fe645xucn {
  d: path("M5 14.75h1.75V17H5Zm4.75 0h1V17h-1Zm3.5 0H15v.75h-1.75Zm0 1.75H15v.5h-1.75Zm4.25-1.75H19V17h-1.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5606nb6s {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5m-.5 4H12m-6.5 3h4");
}

</style>
