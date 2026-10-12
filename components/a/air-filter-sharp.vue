<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fjwo3jbfx"/><path class="qbq7igoku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-filter-sharp" /></template>
<style>
.fjwo3jbfx {
  d: path("M2.75 5.5h18.5v13H2.75z");
}

.qbq7igoku {
  d: path("m5.25 8.5l2.25 7l2.25-7l2.25 7l2.25-7l2.25 7l2.25-7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
