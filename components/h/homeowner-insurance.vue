<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flyo-4bjm"/><path class="wyli5loxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:homeowner-insurance" /></template>
<style>
.flyo-4bjm {
  d: path("M2.5 11a9.5 8 0 0 1 19 0q-2.25-1.5-4.5 0q-2.5-1.5-5 0q-2.5-1.5-5 0q-2.25-1.5-4.5 0m5.1 4.55l3.5-2.625a1.5 1.5 0 0 1 1.8 0l3.5 2.625a1.5 1.5 0 0 1 .6 1.2V20a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 20v-3.25a1.5 1.5 0 0 1 .6-1.2m4.4-4.8v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyli5loxo {
  d: path("M10.5 21.5v-3h3v3");
}

</style>
