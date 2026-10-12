<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k27plyb5p"/><path class="vpsv9hu7z"/><path class="i5ap85-8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gmo-label-sharp" /></template>
<style>
.i5ap85-8w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8.75c2.25 0 2 6.5 4.25 6.5s2-6.5 4.25-6.5m-8.5 6.5c2.25 0 2-6.5 4.25-6.5s2 6.5 4.25 6.5");
}

.k27plyb5p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.35 11.2l3.8-5.15l.6-.8h13.5v13.5H7.75l-.6-.8l-3.8-5.15l-.6-.8z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vpsv9hu7z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 12h.01");
}

</style>
