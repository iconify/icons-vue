<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="a7n7fkbfp"/><path class="n0z2a566z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:last-seen-outline-thin" /></template>
<style>
.a7n7fkbfp {
  d: path("M13 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.f69zonn4h {
  d: path("M4 17a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0z2a566z {
  d: path("M17 15v-3");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
