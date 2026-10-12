<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vgu78uopy"/><path class="n_xas585k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feedback-sharp" /></template>
<style>
.n_xas585k {
  d: path("m12.14 7.07l.89 1.99l.15.32l.34.04l2.17.23l.35.04l-.26.23l-1.62 1.46l-.26.24l.07.34l.46 2.14l.07.34l-.31-.18l-1.89-1.09L12 13l-.3.17l-1.89 1.09l-.31.18l.07-.34l.46-2.14l.07-.34l-.26-.24l-1.62-1.46l-.26-.23l.35-.04l2.17-.23l.34-.04l.15-.32l.89-1.99l.14-.32z");
}

.vgu78uopy {
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
