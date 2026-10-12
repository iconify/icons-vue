<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fnqqojbwr"/><rect class="x0d8itkql"/><path class="sv8xedjhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazmat-suit" /></template>
<style>
.fnqqojbwr {
  d: path("M12 2.75a5 5 0 0 1 5 5v2.5c1.75.6 3.25 2.25 3.25 4.5v6.5H3.75v-6.5c0-2.25 1.5-3.9 3.25-4.5v-2.5a5 5 0 0 1 5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sv8xedjhj {
  d: path("M12 13.75v6M6.75 17.5v2.25m10.5-2.25v2.25");
}

.x0d8itkql {
  width: 4px;
  height: 3px;
  x: 10px;
  y: 6.25px;
  rx: 1.25px;
}

</style>
