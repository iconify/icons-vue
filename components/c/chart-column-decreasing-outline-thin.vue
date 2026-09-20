<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p86p59b-c"/><path class="d-23-qb2d"/><path class="ip4hr0bew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-column-decreasing-outline-thin" /></template>
<style>
.d-23-qb2d {
  d: path("M13 11v9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip4hr0bew {
  d: path("M18 15v5");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p86p59b-c {
  d: path("M8 7v13");
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
