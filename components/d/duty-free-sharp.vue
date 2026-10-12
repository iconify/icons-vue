<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xno6wnbgr"/><path class="f2gugwg_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duty-free-sharp" /></template>
<style>
.f2gugwg_t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.75h.01m4.49 4.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xno6wnbgr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8V6a3 3 0 0 1 6 0v2M6.5 8H19l.14 1.49l.97 10.27l.14 1.49H3.75l.14-1.49l.97-10.27L5 8zm3 9.75l5-5");
}

</style>
