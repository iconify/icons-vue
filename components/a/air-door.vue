<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sarw8qchv"/><path class="k46yhactw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-door" /></template>
<style>
.k46yhactw {
  d: path("m9.25 13l2 2l-2 2");
}

.sarw8qchv {
  d: path("M3.5 21.5V10a5.5 5.5 0 0 1 11 0v11.5m0-13l6-3v14l-6 2ZM6.25 15h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
