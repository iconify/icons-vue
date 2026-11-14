<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axi0xobaa"/><path class="ki-mzib_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automated-parking" /></template>
<style>
.axi0xobaa {
  d: path("M2.5 2.5H12v4m-8.5 5.75v-.204A1.98 1.98 0 0 1 5 10.125l.613-.153a2.63 2.63 0 0 0 1.444-.946l1.155-1.501A2.63 2.63 0 0 1 10.293 6.5h3.414a2.63 2.63 0 0 1 2.081 1.025l1.155 1.501a2.63 2.63 0 0 0 1.444.946l.613.153a1.98 1.98 0 0 1 1.5 1.921v.204A1.75 1.75 0 0 1 18.75 14H5.25a1.75 1.75 0 0 1-1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki-mzib_o {
  d: path("M5.75 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M2.5 21.5h19");
}

</style>
