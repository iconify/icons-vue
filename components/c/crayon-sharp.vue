<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yf7--acfc"/><path class="kl6t7z-cc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crayon-sharp" /></template>
<style>
.kl6t7z-cc {
  d: path("M10 16.48L7.52 14l-.53-.53l-.32.68l-1.41 2.95l-.32.68l.53.53l.22.22l.53.53l.68-.32l2.95-1.41l.68-.32zm6.9-5.84L13.36 7.1m-.7 7.78l-3.54-3.54");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yf7--acfc {
  d: path("m18.31 7.81l-2.12-2.12l-.71-.71l-.71.71l-7.07 7.07l-.71.71l.71.71l2.12 2.12l.71.71l.71-.71l7.07-7.07l.71-.71z");
}

</style>
