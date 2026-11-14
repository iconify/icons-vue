<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw8h17rcr"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-sweep" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.uw8h17rcr {
  d: path("m20.5 3.5l-7 7m.479 2.562L14.5 11.5l-2-2l-7 2.5c.5 3.5 2.5 6.5 6 8.5l.108-.323M9 13.25l2.234 4.021M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
