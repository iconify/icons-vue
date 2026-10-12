<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b86aaxawg"/><path class="jho2glbuy"/><path class="ewaodbbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layers-plus-sharp" /></template>
<style>
.b86aaxawg {
  d: path("m13.11 3.32l7.03 3.61l1.11.57l-1.11.57l-7.03 3.61l-1.11.57l-1.11-.57l-7.03-3.61l-1.11-.57l1.11-.57l7.03-3.61L12 2.75z");
}

.ewaodbbhs {
  d: path("M2.75 16.5L12 21.25l9.25-4.75");
}

.jho2glbuy {
  d: path("M2.75 12L12 16.75L21.25 12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
