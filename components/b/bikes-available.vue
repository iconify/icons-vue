<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cllub2yjr"/><path class="twkdnqbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bikes-available" /></template>
<style>
.cllub2yjr {
  d: path("M3 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m9 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.twkdnqbru {
  d: path("M6.5 11H10l3.5-6l2 6M10 11L8.75 5m-1.5 0h3m3.25 0L13 3.5h2.5M14.75 18l2 2L21 15.75");
}

</style>
