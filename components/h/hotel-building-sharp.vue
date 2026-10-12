<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="voy4t05yy"/><path class="sze-r7bpy"/><path class="yw3eho_ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hotel-building-sharp" /></template>
<style>
.sze-r7bpy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01m-6.01 4h.01m5.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.voy4t05yy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v18.5H5.25zm4.25 3.5h5");
}

.yw3eho_ht {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-3h3v3");
}

</style>
