<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jqdjs7bdr"/><path class="tp2c1ng1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loft-apartment-sharp" /></template>
<style>
.jqdjs7bdr {
  d: path("M2.75 20.5v-12l.61-.44l4.95-3.62l.61-.44v4.5l.61-.44l4.94-3.62l.61-.44v4.5l.61-.44l4.95-3.62l.61-.44v17.25H2.75z");
}

.tp2c1ng1u {
  d: path("M6.25 11.5h11.5v7H6.25zm5.75 0v7M6.25 15h11.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
