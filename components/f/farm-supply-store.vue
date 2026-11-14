<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sf65bdbzy"/><path class="sbv6bfbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farm-supply-store" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbv6bfbfo {
  d: path("M9 9v2a3 3 0 0 0 6 0V9m-3 0v9.25");
}

.sf65bdbzy {
  d: path("M3.714 10.608L6.22 6.013a1.75 1.75 0 0 1 .812-.755l4.244-1.929a1.75 1.75 0 0 1 1.448 0l4.244 1.929a1.75 1.75 0 0 1 .812.755l2.506 4.595a1.75 1.75 0 0 1 .214.838v7.804A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-7.804a1.75 1.75 0 0 1 .214-.838");
}

</style>
