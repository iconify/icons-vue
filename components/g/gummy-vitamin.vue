<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pka927bmv"/><path class="e9ldk6bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gummy-vitamin" /></template>
<style>
.e9ldk6bcb {
  d: path("M9.75 13.5q0-2 1.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pka927bmv {
  d: path("m13.625 5.5l.886 1.363a3.5 3.5 0 0 0 2.051 1.479l1.563.408a1.942 1.942 0 0 1 1.034 3.082l-1.105 1.4a3.5 3.5 0 0 0-.75 2.314l.072 1.735a1.906 1.906 0 0 1-2.626 1.844l-1.425-.583a3.5 3.5 0 0 0-2.65 0l-1.425.583a1.906 1.906 0 0 1-2.626-1.844l.072-1.735a3.5 3.5 0 0 0-.75-2.314l-1.105-1.4A1.942 1.942 0 0 1 5.875 8.75l1.563-.408a3.5 3.5 0 0 0 2.051-1.479l.886-1.363a1.938 1.938 0 0 1 3.25 0");
}

</style>
