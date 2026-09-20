<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mu0i9zbhe"/><path class="abhqbyb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-sandbox-outline-thin" /></template>
<style>
.abhqbyb0v {
  d: path("M14.54 6.56a6 6 0 1 1 -5.08 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu0i9zbhe {
  d: path("M14 2h5a3 3 0 0 1 3 3v14a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3h5");
}

</style>
