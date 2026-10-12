<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wq176fb0q"/><path class="cuiau5bzt"/><path class="bz7b-0rtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deer-sharp" /></template>
<style>
.bz7b-0rtu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13h.01m2.99 0h.01");
}

.cuiau5bzt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 10.25L8.621 6.109L5 4.5m2.25 1.25l.25-3m6.75 7.5l1.129-4.141L19 4.5m-2.25 1.25l-.25-3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wq176fb0q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.25h8c0 3.25-.9 6.75-2.15 9.6a2 2 0 0 1-3.7 0C8.9 17 8 13.5 8 10.25Zm0 1c-1.9.6-3.6.2-4.75-1.25C4.75 9 6.5 8.75 8 9.5Zm8 0c1.9.6 3.6.2 4.75-1.25c-1.5-1-3.25-1.25-4.75-.5Z");
}

</style>
