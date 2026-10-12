<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="huvaqvy6k"/><circle class="cha8ab5ul"/><circle class="i-842mbep"/><circle class="qxh4jaczc"/><circle class="d6uzu6bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-quadrant-sharp" /></template>
<style>
.cha8ab5ul {
  cx: 6.75px;
  cy: 7px;
  r: 1.75px;
}

.d6uzu6bvc {
  cx: 17px;
  cy: 16.5px;
  r: 1.75px;
}

.huvaqvy6k {
  d: path("M12 2.75v18.5M2.75 12h18.5");
}

.i-842mbep {
  cx: 16.75px;
  cy: 7.25px;
  r: 2.25px;
}

.qxh4jaczc {
  cx: 7.25px;
  cy: 16.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
