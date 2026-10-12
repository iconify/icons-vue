<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n8_nikltg"/><path class="u7f-qkb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caravan-camel-sharp" /></template>
<style>
.n8_nikltg {
  d: path("m20.37 9.73l-2.11-2.58l-.63-.77l-.96-.27l-.71-.21l-.96-.27l-.85.53l-1.3.81q-.85.53-1.56 1.24l-.83.83l-.71.71l-.41-.91l-1.05-2.3l-.41-.91l-.71-.71l-.08-.08l-.71-.71l-.99.12l-1.02.13l-.99.12l-.19.75L3 6l.89.45l.47.23l.89.45l.32.95l.49 1.47l.32.95l.6.8l1.05 1.4l.6.8H19.5l.45-.89l.6-1.22l.45-.89zm-1.99 3.77v6.38m-2.63-6.38v6.38m-4.87-6.38v6.38M8.63 13.5v6.38");
}

.u7f-qkb6j {
  d: path("M17.25 13.5V9.75h-4.5v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
