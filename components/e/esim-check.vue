<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bxpviy_9j"/><path class="ofc9bqbqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esim-check" /></template>
<style>
.bxpviy_9j {
  d: path("M14.271 21.5H3.5v-19h9l5 5v7.829");
}

.ofc9bqbqr {
  d: path("M7 7.5h6v6H7ZM14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
