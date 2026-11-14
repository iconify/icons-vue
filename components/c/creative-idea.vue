<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d9sf4hbas"/><path class="z81xmqbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:creative-idea" /></template>
<style>
.d9sf4hbas {
  d: path("M9 17.75v-1.5c-2.5-1.5-4-4-4-6.5a7 7 0 0 1 14 0c0 2.5-1.5 5-4 6.5v1.5ZM9.5 21h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z81xmqbzb {
  d: path("m12 7l.884 2.116L15 10l-2.116.884L12 13l-.884-2.116L9 10l2.116-.884Z");
}

</style>
