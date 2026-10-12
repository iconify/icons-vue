<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z9tzl4vva"/><path class="kfsbxsbmk"/><rect class="a1i1iibet"/><path class="e0_xr-bfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dispatch-desk" /></template>
<style>
.a1i1iibet {
  width: 3px;
  height: 4.5px;
  x: 2.75px;
  y: 11.5px;
  rx: 1.25px;
}

.e0_xr-bfm {
  d: path("M4.25 16v1a2.25 2.25 0 0 0 2.25 2.25h.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfsbxsbmk {
  d: path("M13.5 14.25h4.25m-2.25 4v2.5m-2.75 0h5.5m-14-9.25v-2a3.75 3.75 0 0 1 7.5 0v1");
}

.z9tzl4vva {
  width: 11.25px;
  height: 7.75px;
  x: 10px;
  y: 10.5px;
  rx: 1.5px;
}

</style>
