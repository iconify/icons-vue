<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oq1a22tfe"/><path class="e8acrxy5q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kub-background" /></template>
<style>
.e8acrxy5q {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.6 7.304c.08-.188.188-.36.332-.504L20 11.788l-5.08 5.4l-3.636-3.72a1.5 1.5 0 0 1 2.148 0l1.492 1.524l2.928-3.2L14.932 9a1.56 1.56 0 0 1-.328-1.696zM16 11.8a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-6.932 5.4a1.576 1.576 0 0 0 0-2.2l-2.92-3.18L9.08 9.008l1.488 1.524a1.5 1.5 0 0 0 1.072.456c.404 0 .76-.272 1.04-.564l-3.6-3.616L4 11.82zM10 11.8a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.ft5dv1b6b {
  fill: none;
}

.oq1a22tfe {
  fill: var(--svg-color--4cba64, #4cba64);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
