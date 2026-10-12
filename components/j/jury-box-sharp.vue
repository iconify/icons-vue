<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dng9h31fp"/><circle class="xpr56mbyr"/><path class="xdbv-nbnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jury-box-sharp" /></template>
<style>
.dng9h31fp {
  cx: 8.25px;
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

.xdbv-nbnb {
  d: path("M5 10.25h14M2.75 13h18.5v8.25H2.75zm5.5 2.5v3.25m7.5-3.25v3.25");
}

.xpr56mbyr {
  cx: 15.75px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
