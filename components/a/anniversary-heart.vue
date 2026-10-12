<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og90z_wuj"/><circle class="shutjyb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anniversary-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og90z_wuj {
  d: path("m12 18.9l-5.95-5.95C4.78 11.72 3.5 10.23 3.5 8.28c0-2.59 2.09-4.68 4.68-4.68c1.49 0 2.54.43 3.82 1.7c1.28-1.27 2.33-1.7 3.82-1.7c2.59 0 4.68 2.09 4.68 4.68c0 1.95-1.27 3.44-2.55 4.67Z");
}

.shutjyb7t {
  cx: 12px;
  cy: 10.75px;
  r: 2.5px;
}

</style>
