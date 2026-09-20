<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngcuq3bxa"/><path class="kwcqu2u9a"/><path class="ef-jgqbdk"/><path class="k4p4tzbhq"/><path class="y_j9zzqtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lock-door-duotone-thin" /></template>
<style>
.ef-jgqbdk {
  d: path("M4 3v18h10V3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4p4tzbhq {
  d: path("M17 13v6h5v-6Z");
}

.kwcqu2u9a {
  fill: currentColor;
  d: path("M17 13v6h5v-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ngcuq3bxa {
  fill: currentColor;
  d: path("M4 3v18h10V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y_j9zzqtv {
  d: path("M17.5 13a2 2 0 0 1 4 0");
}

</style>
