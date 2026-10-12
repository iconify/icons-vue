<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xoq3z2bsb"/><path class="a6kjpy2nm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cumulative-chart-sharp" /></template>
<style>
.a6kjpy2nm {
  d: path("M7 9.5c3.25 0 4-4.5 7.5-5.25c2-.4 3.5-.5 5.75-.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xoq3z2bsb {
  d: path("M3.75 3.75v16.5h16.5M8 16.75V13.5m4 3.25V11.5m4 5.25v-2.5");
}

</style>
