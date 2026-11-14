<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kaw7ibbdn"/><path class="v7cpgqhly"/><path class="g_fvw6bgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-triadic" /></template>
<style>
.g_fvw6bgl {
  d: path("M11.5 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kaw7ibbdn {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.v7cpgqhly {
  d: path("M2.5 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
