<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g0hbly4ee"/><path class="lylcpsbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:armchair-sharp" /></template>
<style>
.g0hbly4ee {
  d: path("M6.25 10.25v-7.5h11.5v7.5");
}

.lylcpsbcu {
  d: path("M3.25 12.5a2.25 2.25 0 0 1 4.5 0v1.75h8.5V12.5a2.25 2.25 0 0 1 4.5 0V20H3.25v-2ZM6 20v1.25M18 20v1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
