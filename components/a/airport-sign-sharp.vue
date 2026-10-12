<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="uwca_bbda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-sign-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.uwca_bbda {
  d: path("M12 5h1.25v4.75l5 3v2.5l-5-1.25v2l1.5 1.25v1.25L12 17.75l-2.75.75v-1.25l1.5-1.25v-2l-5 1.25v-2.5l5-3V5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
