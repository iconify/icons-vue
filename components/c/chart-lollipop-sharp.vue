<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t_v36abap"/><circle class="c_pvp7bsw"/><circle class="f7q4j1b4c"/><circle class="n7wblqmuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-lollipop-sharp" /></template>
<style>
.c_pvp7bsw {
  cx: 8.5px;
  cy: 11.5px;
  r: 1.75px;
}

.f7q4j1b4c {
  cx: 13.75px;
  cy: 6px;
  r: 1.75px;
}

.n7wblqmuf {
  cx: 19px;
  cy: 12.75px;
  r: 1.75px;
}

.t_v36abap {
  d: path("M3.75 3.75v16.5h16.5m-11.75-3v-4m5.25 4v-9.5m5.25 9.5V14.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
