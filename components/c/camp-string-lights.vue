<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="amfjlc-na"/><path class="ymk_5xbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-string-lights" /></template>
<style>
.amfjlc-na {
  d: path("M2.5 4v17m19-17v17M2.5 5q9.5 10 19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymk_5xbop {
  d: path("M5 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 1.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
