<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="uuf2qibax"/><path class="fzu88m-nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:furniture-catalog" /></template>
<style>
.fzu88m-nb {
  d: path("M9 8.25v-1.5a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

.uuf2qibax {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5m-12-2.75v-4a1.5 1.5 0 0 1 3 0v1.5h3v-1.5a1.5 1.5 0 0 1 3 0v4");
}

</style>
