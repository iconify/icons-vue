<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bepgkac6a"/><rect class="xo9x3ubms"/><path class="f_4vj5bmx"/><rect class="sn1km8b3x"/><path class="grnq65bnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:box-plot" /></template>
<style>
.bepgkac6a {
  d: path("M7.5 4.75v3m0 8.25v3.5");
}

.f_4vj5bmx {
  d: path("M6.25 12.25h2.5m7.75-9.5v3m0 7.5v4.5");
}

.grnq65bnt {
  d: path("M15.25 9.5h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sn1km8b3x {
  width: 4.5px;
  height: 7.5px;
  x: 14.25px;
  y: 5.75px;
  rx: 1px;
}

.xo9x3ubms {
  width: 4.5px;
  height: 8.25px;
  x: 5.25px;
  y: 7.75px;
  rx: 1px;
}

</style>
