<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_2z93bzc"/><path class="c3bibzbjd"/><path class="od8m85avy"/><path class="n3p0zmbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:galaxy-duotone-thin" /></template>
<style>
.c3bibzbjd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12c0 -3 3 -5 6 -3s2 8 -3 10c-6 2 -11 -2 -11 -8 0 -5 5 -8 10 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_2z93bzc {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n3p0zmbop {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.od8m85avy {
  d: path("M12 12c0 -3 3 -5 6 -3s2 8 -3 10c-6 2 -11 -2 -11 -8 0 -5 5 -8 10 -8");
}

</style>
