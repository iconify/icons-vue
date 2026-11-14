<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g3_tqjb5f"/><path class="ctd21sbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:butterflyfish" /></template>
<style>
.ctd21sbka {
  d: path("M11.5 5q1.5 7 0 14m-3.25-7.5h.01");
}

.g3_tqjb5f {
  d: path("m3 12l3-2c1-6.5 10-7 11.5-.5L21 7v10l-3.5-2.5C16 21 7 20.5 6 14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
