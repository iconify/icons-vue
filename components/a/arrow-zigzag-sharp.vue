<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="li2ulccvr"/><path class="kxr94xglj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-zigzag-sharp" /></template>
<style>
.kxr94xglj {
  d: path("M18.25 9.75L20.5 12l-2.25 2.25");
}

.li2ulccvr {
  d: path("M3.75 12L7 7.5l3.5 9l3.5-9l3 4.5h3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
