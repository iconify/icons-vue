<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="zsqnb834t"/><circle class="a24yqwbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magazine-sharp" /></template>
<style>
.a24yqwbfv {
  cx: 12px;
  cy: 14.75px;
  r: 3.25px;
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zsqnb834t {
  d: path("M6.75 5.75h10.5v3H6.75z");
}

</style>
