<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="becjbsbun"/><path class="gudriqs8e"/><circle class="wk00ypvul"/><path class="bdhq7u78x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:license-agreement" /></template>
<style>
.bdhq7u78x {
  d: path("M18.75 8v13m0-4.5h2m-2 3h2");
}

.becjbsbun {
  width: 11.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.gudriqs8e {
  d: path("M6 7h5m-5 3.25h3.5M6 17h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wk00ypvul {
  cx: 18.75px;
  cy: 6px;
  r: 2px;
}

</style>
