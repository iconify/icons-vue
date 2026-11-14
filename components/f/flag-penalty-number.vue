<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5yulux_f"/><path class="jmn-s2b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flag-penalty-number" /></template>
<style>
.f5yulux_f {
  d: path("M4.5 2.5v19M4.5 4H19a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmn-s2b2l {
  d: path("M10.5 7H14a1.5 1.5 0 0 1 1.5 1.5v2A1.5 1.5 0 0 1 14 12h-3.5A1.5 1.5 0 0 1 9 10.5v-2A1.5 1.5 0 0 1 10.5 7");
}

</style>
