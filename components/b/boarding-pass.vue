<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jc2_tacnn"/><path class="u3s9-wsry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boarding-pass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jc2_tacnn {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 2px;
}

.u3s9-wsry {
  d: path("M15.5 8.5v1.25m0 1.65v1.25m0 1.6v1.25M6.25 10h5.5m-5.5 4h3.5");
}

</style>
