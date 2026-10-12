<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h81zrmtfz"/><path class="cucy-8bke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:income-statement" /></template>
<style>
.cucy-8bke {
  d: path("M8 7h8m-8 3.25h5m-5 7l2.5-2.5l2 2l3.5-3.5");
}

.h81zrmtfz {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
