<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="da3dvjdqa"/><path class="sawgdkbmg"/><path class="o116xmboq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:attention-map-sharp" /></template>
<style>
.da3dvjdqa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5q4.75-6.5 9.5 0q-4.75 6.5-9.5 0Z");
}

.o116xmboq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 10.75h3.75v3.75h-3.75zm6.75 0h3.75v3.75H17.5zm-6.75 6.75h3.75v3.75h-3.75zm6.75 0h3.75v3.75H17.5z");
}

.sawgdkbmg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 6.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
