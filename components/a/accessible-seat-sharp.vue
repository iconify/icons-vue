<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r09w-tbht"/><path class="zwnbbacwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-seat-sharp" /></template>
<style>
.r09w-tbht {
  d: path("M5.25 4.25v-1.5h3V13h10.5v3.5H5.25v-2ZM8 16.5v4.75m8.5-4.75v4.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwnbbacwk {
  d: path("m16.39 3.07l.89 1.99l.15.32l.34.04l2.17.23l.35.04l-.26.23l-1.62 1.46l-.26.24l.07.34l.46 2.14l.07.34l-.31-.18l-1.89-1.09l-.3-.17l-.3.17l-1.89 1.09l-.31.18l.07-.34l.46-2.14l.07-.34l-.26-.24l-1.62-1.46l-.26-.23l.35-.04l2.17-.23l.34-.04l.15-.32l.89-1.99l.14-.32z");
}

</style>
