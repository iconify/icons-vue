<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r6ni9ykjg"/><path class="coaj1tg0l"/><path class="oge8ivj8c"/><path class="tpktuzbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-fly-ball" /></template>
<style>
.coaj1tg0l {
  d: path("M9 11q2 4.5 0 9m6-9q-2 4.5 0 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oge8ivj8c {
  d: path("M3.5 13a8.5 8 0 0 1 17 0");
}

.r6ni9ykjg {
  d: path("M6.5 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.tpktuzbem {
  d: path("M17.75 11.25L20.5 13l1.5-2.75");
}

</style>
