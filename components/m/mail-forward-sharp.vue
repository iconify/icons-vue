<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t0c9a54sn"/><path class="v4z1i4ejk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-forward-sharp" /></template>
<style>
.t0c9a54sn {
  d: path("M2.75 7.25h14.5v12H2.75z");
}

.v4z1i4ejk {
  d: path("m6 10.75l3.65 2.75L11 14.512l1.35-1.012L16 10.75m2.75-8L21 5l-2.25 2.25M21 5h-6v4.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
