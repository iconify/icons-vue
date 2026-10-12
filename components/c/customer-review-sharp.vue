<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="poazpiu-g"/><path class="dlzpjg0nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customer-review-sharp" /></template>
<style>
.dlzpjg0nf {
  d: path("m12.14 6.82l.89 1.99l.15.32l.34.04l2.17.23l.35.04l-.26.23l-1.62 1.46l-.26.24l.07.34l.46 2.14l.07.34l-.31-.18l-1.89-1.09l-.3-.17l-.3.17l-1.89 1.09l-.31.18l.07-.34l.46-2.14l.07-.34l-.26-.24l-1.62-1.46l-.26-.23l.35-.04l2.17-.23l.34-.04l.15-.32l.89-1.99l.14-.32z");
}

.poazpiu-g {
  d: path("M5.25 3.75h16v13.5h-9l-4 3.5l-1.006.9l.006-1.35v-3.05h-4.5V3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
