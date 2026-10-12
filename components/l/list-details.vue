<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lcmqtccog"/><path class="wqbhr255g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:list-details" /></template>
<style>
.lcmqtccog {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6h11m-11 6h11m-11 6h11");
}

.wqbhr255g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.25 6h.01m-.01 6h.01m-.01 6h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
