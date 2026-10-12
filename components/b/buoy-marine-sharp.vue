<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tebp1dbgt"/><circle class="c70vv4bjr"/><path class="r7slpvz7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buoy-marine-sharp" /></template>
<style>
.c70vv4bjr {
  cx: 12px;
  cy: 4.75px;
  r: 1.75px;
}

.r7slpvz7b {
  d: path("M2.75 20.75C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

.tebp1dbgt {
  d: path("m6.46 16.53l1.83-6.31l.21-.72h7l.21.72l1.83 6.31l.21.72H6.25zm.94-3.03h9.2m-6.85-4l1.25-3m3.25 3L13 6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
