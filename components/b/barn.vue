<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sf65bdbzy"/><path class="g2zimsbja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barn" /></template>
<style>
.g2zimsbja {
  d: path("M9.5 13.5h5A1.5 1.5 0 0 1 16 15v4.5a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 19.5V15a1.5 1.5 0 0 1 1.5-1.5m-1.5 0l8 7.5m0-7.5L8 21m4-14za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 12 10a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 12 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sf65bdbzy {
  d: path("M3.714 10.608L6.22 6.013a1.75 1.75 0 0 1 .812-.755l4.244-1.929a1.75 1.75 0 0 1 1.448 0l4.244 1.929a1.75 1.75 0 0 1 .812.755l2.506 4.595a1.75 1.75 0 0 1 .214.838v7.804A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-7.804a1.75 1.75 0 0 1 .214-.838");
}

</style>
