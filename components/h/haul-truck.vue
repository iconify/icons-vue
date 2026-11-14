<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oitp1ibsv"/><path class="mbo0o-b5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:haul-truck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbo0o-b5r {
  d: path("M14.5 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.oitp1ibsv {
  d: path("m2.793 11.426l-.188-1.874a1.5 1.5 0 0 1 .851-1.505l6.808-3.225a1.5 1.5 0 0 1 2.113 1.062l.389 1.944a1.5 1.5 0 0 1-.856 1.662l-7.009 3.155a1.5 1.5 0 0 1-2.108-1.219M16 13.5v-6h2.75L21.5 11v2.5m-19 0h19M4 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
