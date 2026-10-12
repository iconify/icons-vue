<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="q3jop5grj"/><circle class="tq0ogqbac"/><path class="xe5j2gbzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earphones-wired-sharp" /></template>
<style>
.q3jop5grj {
  cx: 7px;
  cy: 5.25px;
  r: 2.5px;
}

.tq0ogqbac {
  cx: 17px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe5j2gbzm {
  d: path("M7 7.75v3.5a5 5 0 0 0 5 5v5m5-13.5v3.5a5 5 0 0 1-5 5");
}

</style>
