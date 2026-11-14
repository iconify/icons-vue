<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvhmoq7dx"/><path class="xj1-hmhab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fibonacci-spiral" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvhmoq7dx {
  d: path("M3.75 6h16.5a1.5 1.5 0 0 1 1.5 1.5v9a1.5 1.5 0 0 1-1.5 1.5H3.75a1.5 1.5 0 0 1-1.5-1.5v-9A1.5 1.5 0 0 1 3.75 6m10.5 0v12m0-4.5h7.5m-4.5 0V18");
}

.xj1-hmhab {
  d: path("M2.25 18a12 12 0 0 1 12-12a7.5 7.5 0 0 1 7.5 7.5a4.5 4.5 0 0 1-4.5 4.5");
}

</style>
