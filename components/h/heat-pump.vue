<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="saayrfb7u"/><circle class="to76gxjla"/><path class="srvysyb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heat-pump" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.saayrfb7u {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.srvysyb_o {
  d: path("M9.25 11V8.25m0 2.75l2.4 1.4M9.25 11l-2.4 1.4m9.4-4.4v6m2.5-6v6m-12.5 4.25v3m11.5-3v3");
}

.to76gxjla {
  cx: 9.25px;
  cy: 11px;
  r: 4.25px;
}

</style>
