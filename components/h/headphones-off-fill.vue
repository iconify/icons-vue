<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="he_aj2bnr"/><path class="exbn0709o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off-fill" /></template>
<style>
.exbn0709o {
  d: path("M3 12C3 9.5147 4.0074 7.2647 5.636 5.636M9.1256 3.4688C10.0282 3.1648 10.9949 3 12 3C16.9706 3 21 7.0294 21 12M2 2L22 22");
}

.he_aj2bnr {
  fill: currentColor;
  d: path("M2 12C2 10.3431 3.3431 9 5 9L5 9C6.6569 9 8 10.3431 8 12L8 19C8 20.6569 6.6569 22 5 22L5 22C3.3431 22 2 20.6569 2 19L2 12ZM21.1213 21.1213C20.5784 21.6642 19.8284 22 19 22L19 22C17.3431 22 16 20.6569 16 19L16 16ZM16.3763 12.1337C16.1165 11.8739 16.0201 11.4926 16.1252 11.1406C16.4945 9.9025 17.6419 9 19 9L19 9C20.6569 9 22 10.3431 22 12L22 15.3431C22 15.7476 21.7564 16.1122 21.3827 16.267C21.009 16.4218 20.5789 16.3362 20.2929 16.0502L16.3763 12.1337Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
