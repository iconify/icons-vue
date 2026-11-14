<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8wiivb6g"/><path class="gg3_3ob4k"/><path class="bgnk2uojt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-join" /></template>
<style>
.bgnk2uojt {
  fill: currentColor;
  d: path("M11.5 10h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

.gg3_3ob4k {
  d: path("M12.625 10h6.25a2.625 2.625 0 0 1 2.625 2.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-6.25A2.625 2.625 0 0 1 10 18.875v-6.25A2.625 2.625 0 0 1 12.625 10M2.5 6.25H14M14 14h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8wiivb6g {
  d: path("M5.125 2.5h6.25A2.625 2.625 0 0 1 14 5.125v6.25A2.625 2.625 0 0 1 11.375 14h-6.25A2.625 2.625 0 0 1 2.5 11.375v-6.25A2.625 2.625 0 0 1 5.125 2.5");
}

</style>
