<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzt8fd71i"/><path class="vezq7pbcc"/><path class="ymhuvfz3p"/><path class="hxtix3e9b"/><path class="y0y0ccsoe"/><path class="cxgftibra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chemical-reaction-outline-thin" /></template>
<style>
.cxgftibra {
  d: path("m12 10 2 2 -2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxtix3e9b {
  d: path("M15 6v11h6V6");
}

.rzt8fd71i {
  d: path("M2 6h8");
}

.vezq7pbcc {
  d: path("M3 6v11h6V6");
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

.ymhuvfz3p {
  d: path("M14 6h8");
}

</style>
