<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-4bk_b4n"/><path class="oej_05bgt"/><path class="lp4aq-bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dividend-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lp4aq-bgr {
  d: path("M14 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.o-4bk_b4n {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

.oej_05bgt {
  d: path("M4 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
