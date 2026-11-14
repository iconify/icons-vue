<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m379m8btb"/><path class="x9cv2hk7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:festival-tent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m379m8btb {
  d: path("m4.533 17.717l6.054-8.284a1.75 1.75 0 0 1 2.826 0l6.054 8.284a1.75 1.75 0 0 1-1.413 2.783H5.946a1.75 1.75 0 0 1-1.413-2.783M12 2.5v5m1.379-4.409l.371.159a.816.816 0 0 1 0 1.5l-.371.159A.99.99 0 0 1 12 4a.99.99 0 0 1 1.379-.909");
}

.x9cv2hk7p {
  d: path("M8.5 20.5L12 13l3.5 7.5");
}

</style>
