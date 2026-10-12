<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="tdul6ibzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bubble-wrap-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.tdul6ibzo {
  d: path("M7.25 5.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5Zm9.5 0a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5ZM7.25 15a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5Zm9.5 0a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5ZM12 10.25a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
