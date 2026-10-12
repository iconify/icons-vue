<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="upddb4dxn"/><path class="bc9kdcbga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dehumidifier" /></template>
<style>
.bc9kdcbga {
  d: path("M12 6.5c-1.5 1.75-2.75 3.25-2.75 4.75a2.75 2.75 0 0 0 5.5 0c0-1.5-1.25-3-2.75-4.75m-3.75 11h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upddb4dxn {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
