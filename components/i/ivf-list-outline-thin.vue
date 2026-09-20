<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5ic9acln"/><path class="tzv123bil"/><path class="trdlwwbvq"/><path class="f-6kshnwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ivf-list-outline-thin" /></template>
<style>
.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.f-6kshnwt {
  d: path("M11 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.trdlwwbvq {
  d: path("M15 10v5");
}

.tzv123bil {
  d: path("M9 10v5");
}

</style>
