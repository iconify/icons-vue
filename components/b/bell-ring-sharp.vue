<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rptqo5c7w"/><path class="jh_vo5bef"/><path class="iwk7burpc"/><path class="hysb4uu-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-ring-sharp" /></template>
<style>
.hysb4uu-b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 4.5a7 7 0 0 1 4.5 5");
}

.iwk7burpc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.5 20.6h.01");
}

.jh_vo5bef {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.86 7.77c2.35-.85 3.69.79 4.78 3.05s2.26 3.43 4.17 3.7l1.362.653l-1.222.887l-10.72 3.9l-1.523.12l.633-1.39c1.29-1.43 1.44-3.08.82-5.51s-.65-4.55 1.7-5.41Z");
}

.rptqo5c7w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.49 4.91a1.25 1.25-20 0 1 2.35-.86l1.2 3.29l-2.35.86Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
