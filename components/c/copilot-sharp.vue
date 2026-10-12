<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="q0ext1bfu"/><path class="mfotwpbta"/><path class="ozp811btq"/><path class="ycv4ynbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:copilot-sharp" /></template>
<style>
.mfotwpbta {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.5c0-2.6 1.7-4.25 3.75-4.25s3.75 1.65 3.75 4.25v1h-7.5zM17.5 3.25v2.5m-3.25.75h6.5V12h-6.5z");
}

.ozp811btq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 9.25h.01m2.49 0h.01");
}

.q0ext1bfu {
  cx: 6.5px;
  cy: 8.75px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ycv4ynbfw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 19.5c0-2.6 1.7-4.25 3.75-4.25s3.75 1.65 3.75 4.25v1h-7.5z");
}

</style>
