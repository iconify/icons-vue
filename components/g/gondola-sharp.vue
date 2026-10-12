<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wlh0rfx8m"/><path class="lh_lqlb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gondola-sharp" /></template>
<style>
.lh_lqlb_s {
  d: path("M20.5 9V6.25H19M7.25 2.75l2.75 8.5M3.25 21c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

.wlh0rfx8m {
  d: path("M2.75 11c2.5 1.75 5.5 2.5 9.25 2.5c3.5 0 6.25-1.25 8-4.5l.986-.929l.264 1.329C20.75 14 17 17 12 17c-4.6 0-7.85-2.15-9.25-6Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
