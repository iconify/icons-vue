<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nj5ucobzf"/><circle class="j3jribyxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eclipse-sharp" /></template>
<style>
.j3jribyxk {
  cx: 14.75px;
  cy: 9.25px;
  r: 6.5px;
}

.nj5ucobzf {
  cx: 9.75px;
  cy: 14.25px;
  r: 7px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
