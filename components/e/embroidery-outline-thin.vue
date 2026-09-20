<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_ssmh9ez"/><path class="mp8d-bcnh"/><path class="qm__pqbae"/><path class="uuj0dsv7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embroidery-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mp8d-bcnh {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.qm__pqbae {
  d: path("m8 10 3 3");
}

.uuj0dsv7p {
  d: path("m13 11 3 3");
}

</style>
