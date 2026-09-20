<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5ztjmaaw"/><path class="nmydmacrd"/><path class="t4q7b5q6x"/><path class="x1gscpb4z"/><path class="pmuiqo95v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:campsite-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmydmacrd {
  d: path("m12 14 5 -5 5 5Z");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.t4q7b5q6x {
  d: path("M7 11v3");
}

.w5ztjmaaw {
  d: path("m2 14 5 -5 5 5Z");
}

.x1gscpb4z {
  d: path("M17 11v3");
}

</style>
