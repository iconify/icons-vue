<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5j42c8km"/><path class="f7hnb4ftm"/><path class="xmopbdc-t"/><path class="xgrfb-bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laundry-basket-duotone-thin" /></template>
<style>
.f7hnb4ftm {
  d: path("M5 10v10h14V10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5j42c8km {
  fill: currentColor;
  d: path("M5 10v10h14V10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xmopbdc-t {
  d: path("M5 15h14");
}

</style>
