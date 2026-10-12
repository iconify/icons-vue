<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="owcfk0-vx"/><path class="ad-utccym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alarm-off" /></template>
<style>
.ad-utccym {
  d: path("m6.75 19.5l-1.5 1.75M20.5 6.5l-3.25-2.75m-13.5 0l16.5 16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.owcfk0-vx {
  cx: 12px;
  cy: 12.75px;
  r: 7.5px;
}

</style>
