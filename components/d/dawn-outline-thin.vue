<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="vl804rbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dawn-outline-thin" /></template>
<style>
.bnhdslb0j {
  d: path("M19 8v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k15q4tbdt {
  d: path("M6 19a6 6 0 0 1 12 0");
}

.vl804rbny {
  d: path("M16.5 10.5 19 8l2.5 2.5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
