<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0fpqkbin"/><path class="dhpe9gbco"/><path class="weddopsmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-vertical-duotone" /></template>
<style>
.dhpe9gbco {
  stroke-opacity: 0.4;
  d: path("M3 16L3 18C3 19.6569 4.3431 21 6 21M10.5 21L13.5 21M18 21C19.6569 21 21 19.6569 21 18L21 16");
}

.n0fpqkbin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2C3.7909 2 2 3.7909 2 6L2 8C2 8.5523 2.4477 9 3 9L21 9C21.5523 9 22 8.5523 22 8L22 6C22 3.7909 20.2091 2 18 2L6 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.weddopsmh {
  d: path("M3 12L21 12");
}

</style>
