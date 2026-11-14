<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucw6ft0sh"/><path class="k9e20tbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:game-asset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9e20tbsu {
  d: path("M9 4.25L12 6l3-1.75M12 6v3.5");
}

.ucw6ft0sh {
  d: path("M4.5 12.25v7.25a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-7.25Zm0 0l-2-2.75m17 2.75l2-2.75m-8.744-6.559l1.5.875A1.5 1.5 0 0 1 15 5.112v1.776a1.5 1.5 0 0 1-.744 1.296l-1.5.875a1.5 1.5 0 0 1-1.512 0l-1.5-.875A1.5 1.5 0 0 1 9 6.888V5.112a1.5 1.5 0 0 1 .744-1.296l1.5-.875a1.5 1.5 0 0 1 1.512 0");
}

</style>
