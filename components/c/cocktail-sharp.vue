<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f_odwxbfl"/><path class="hgg6cmb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cocktail-sharp" /></template>
<style>
.f_odwxbfl {
  d: path("M10.75 2.75h2.5m-6 7.5C7.5 7.5 9.5 5.75 12 5.75s4.5 1.75 4.75 4.5Z");
}

.hgg6cmb0z {
  d: path("M8 10.25h9.25l-.14 1.24l-.97 8.52l-.14 1.24H8l-.14-1.24l-.97-8.52l-.14-1.24zm-.85 3.25h9.7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
