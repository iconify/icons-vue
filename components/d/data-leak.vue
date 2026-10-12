<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pvqhyyhlw"/><path class="cdrtyp4uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:data-leak" /></template>
<style>
.cdrtyp4uy {
  d: path("M3.75 5.75c0 1.65 2.7 3 6 3s6-1.35 6-3m-12 4.75c0 1.65 2.7 3 6 3s6-1.35 6-3m3.5 4c1.2 1.6 2 2.75 2 3.75a2 2 0 0 1-4 0c0-1 .8-2.15 2-3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pvqhyyhlw {
  d: path("M3.75 5.75c0-1.65 2.7-3 6-3s6 1.35 6 3v9.5c0 1.65-2.7 3-6 3s-6-1.35-6-3Z");
}

</style>
