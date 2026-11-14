<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="es8f7jbsw"/><path class="rseep8b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dna-test" /></template>
<style>
.es8f7jbsw {
  d: path("M5 3c0 4.5 6 4.5 6 9s-6 4.5-6 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rseep8b2h {
  d: path("M11 3c0 4.5-6 4.5-6 9s6 4.5 6 9m4-2.5l2 2l4.5-4.5");
}

</style>
