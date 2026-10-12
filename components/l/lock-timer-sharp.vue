<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="palpaupib"/><circle class="z2tlmlb4i"/><path class="x0pdqfwra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lock-timer-sharp" /></template>
<style>
.palpaupib {
  d: path("M2.75 10.25h9v9.5h-9zm2 0V7.5a2.5 2.5 0 0 1 5 0v2.75");
}

.x0pdqfwra {
  d: path("M17.75 14.5V16l1 1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2tlmlb4i {
  cx: 17.75px;
  cy: 16px;
  r: 3.5px;
}

</style>
