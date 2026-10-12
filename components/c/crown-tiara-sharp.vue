<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i68qg73pp"/><path class="a4sqm4byg"/><path class="ab9635v4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crown-tiara-sharp" /></template>
<style>
.a4sqm4byg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11h.01");
}

.ab9635v4b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 20h17.5");
}

.i68qg73pp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 16V7.5l.69.73l2.87 3.04l.69.73l.54-.84l3.42-5.32L12 5l.54.84l3.42 5.32l.54.84l.69-.73l2.87-3.04l.69-.73V17H3.25z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
