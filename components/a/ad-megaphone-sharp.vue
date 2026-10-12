<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u0rps8cvl"/><path class="vyk61ls5q"/><path class="xb3xm_rdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ad-megaphone-sharp" /></template>
<style>
.u0rps8cvl {
  d: path("M2.75 12.5v-1h4.5L14.5 8l1.525-.881L16 8.88v10.74l.025 1.761L14.5 20.5L7.25 17h-4.5v-1Z");
}

.vyk61ls5q {
  d: path("M5 17.75v3.5h3v-3.5m10.75-6l2.552 2.5l-2.552 2.5m-3.5-14h6v4.5h-6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb3xm_rdf {
  d: path("m17.25 6l1-2l1 2");
}

</style>
