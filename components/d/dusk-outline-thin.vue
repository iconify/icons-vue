<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="kyf663bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dusk-outline-thin" /></template>
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

.kyf663bil {
  d: path("M16.5 11.5 19 14l2.5 -2.5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
