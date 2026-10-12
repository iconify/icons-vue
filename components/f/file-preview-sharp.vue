<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z2li5jbjy"/><path class="gebtxhjud"/><path class="xr8t5tbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-preview-sharp" /></template>
<style>
.gebtxhjud {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5m-11 4h4M14 17.5c1.75-3.25 5.5-3.25 7.25 0c-1.75 3.25-5.5 3.25-7.25 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xr8t5tbva {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.625 17.5h.01");
}

.z2li5jbjy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

</style>
