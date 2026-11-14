<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqjei3fhk"/><path class="vri2fou2m"/><path class="k_9_2v4ce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-weaving" /></template>
<style>
.k_9_2v4ce {
  d: path("m3.5 17l4.25-4.5L12 17l4.25-4.5L20.5 17");
}

.pqjei3fhk {
  d: path("M3.5 9.5h17v8A2.5 2.5 0 0 1 18 20H6a2.5 2.5 0 0 1-2.5-2.5Zm3 0a5.5 5.5 0 0 1 11 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vri2fou2m {
  d: path("M3.5 12.5L7.75 17L12 12.5l4.25 4.5l4.25-4.5");
}

</style>
