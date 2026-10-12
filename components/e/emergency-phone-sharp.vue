<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="hr8ztacit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emergency-phone-sharp" /></template>
<style>
.hr8ztacit {
  d: path("M7 7.5h2l1 2.75l-1.5 1A7.5 7.5 0 0 0 12.25 15l1-1.5l2.75 1V18h-1.5a10 10 0 0 1-9-9V7.5zm9-1.75v4.5M13.75 8h4.5");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
