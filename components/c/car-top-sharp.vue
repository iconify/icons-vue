<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tme2kebfa"/><path class="k5s6k3bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-top-sharp" /></template>
<style>
.k5s6k3bhg {
  d: path("M8.75 8.75L12 7.125l3.25 1.625M9 17l3 1.125L15 17M6.75 9.25h-2m12.5 0h2");
}

.tme2kebfa {
  d: path("M6.75 2.75h10.5v18.5H6.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
