<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t6ozvr6zj"/><circle class="z1qpurb8m"/><path class="qnrk4qblw"/><circle class="yjztigbem"/><path class="bq857wblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:family-sharp" /></template>
<style>
.bq857wblc {
  d: path("M10.75 20.5v-3h2.5v3");
}

.qnrk4qblw {
  d: path("M2.75 20.5V17a2.5 2.5 0 0 1 5 0v3.5m8.5 0V17a2.5 2.5 0 0 1 5 0v3.5");
}

.t6ozvr6zj {
  cx: 5.25px;
  cy: 9px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjztigbem {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

.z1qpurb8m {
  cx: 18.75px;
  cy: 9px;
  r: 2.5px;
}

</style>
