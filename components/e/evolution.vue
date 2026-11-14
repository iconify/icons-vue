<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cabnbibqv"/><path class="k7lihoihe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:evolution" /></template>
<style>
.cabnbibqv {
  d: path("M16.5 3c-3.5 3.25 1.25 8-2.25 11.25C11 17.75 6.25 13 3 16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7lihoihe {
  d: path("M21 7.5C17.75 11 13 6.25 9.75 9.75C6.25 13 11 17.75 7.5 21M9.75 9.75l4.5 4.5M15.5 4.5l4 4m-15 7l4 4");
}

</style>
