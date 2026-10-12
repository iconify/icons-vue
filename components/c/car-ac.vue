<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w3e3x2b8z"/><rect class="oacbv8bcs"/><path class="qji1xg-_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-ac" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oacbv8bcs {
  width: 18.5px;
  height: 5.75px;
  x: 2.75px;
  y: 15.5px;
  rx: 2px;
}

.qji1xg-_z {
  d: path("M7.5 17.5v1.75M12 17.5v1.75m4.5-1.75v1.75");
}

.w3e3x2b8z {
  d: path("M12 3.75v9.5M7.89 6.13l8.22 4.75m-8.22 0l8.22-4.75");
}

</style>
