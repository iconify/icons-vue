<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a1ih3gb6t"/><path class="etkdmvbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frequently-bought-together" /></template>
<style>
.a1ih3gb6t {
  d: path("m5.5 8l3.25 1.75v4.5L5.5 16l-3.25-1.75v-4.5Zm13 0l3.25 1.75v4.5L18.5 16l-3.25-1.75v-4.5ZM12 10.25v3.5M10.25 12h3.5");
}

.etkdmvbup {
  d: path("M2.25 9.75L5.5 11.5l3.25-1.75M5.5 11.5V16m9.75-6.25l3.25 1.75l3.25-1.75M18.5 11.5V16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
