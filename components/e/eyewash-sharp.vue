<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="dthul3b4z"/><path class="m9me6bb5j"/><path class="qqfe1sb6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eyewash-sharp" /></template>
<style>
.dthul3b4z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.5q2.625-3 6-3c3.375 0 4.25 1 6 3q-2.625 3-6 3c-3.375 0-4.25-1-6-3Z");
}

.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.qqfe1sb6s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17.75V15.5L11 14m3.5 3.75V15.5L13 14m-5.5 4h9");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
