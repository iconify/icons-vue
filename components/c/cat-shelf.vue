<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bel18jb3i"/><path class="p-nwckbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-shelf" /></template>
<style>
.bel18jb3i {
  d: path("M2.5 14h19m-17 0c0-2.5 1.75-4 4.5-4h4.25c.25-2 1-3 1.75-3.75l.5-1.5L16.75 6h1L19 4.75l.5 1.5C20.25 7 20.75 8 20.75 9.5c0 2-.5 3.5-1.25 4.5");
}

.p-nwckbbq {
  d: path("M4.5 13c-1.5.5-1.75 3-1 5.5m4-4.5v4.5L11 14m5.5 0v4.5L13 14m4.75-4h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
