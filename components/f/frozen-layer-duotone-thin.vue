<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-kvq4blj"/><path class="mg7aqnbsf"/><path class="a4k633d3m"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frozen-layer-duotone-thin" /></template>
<style>
.a4k633d3m {
  d: path("M3 12a2.5 2.5 0 0 1 2.5 -2.5h13A2.5 2.5 0 0 1 21 12a2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.o-kvq4blj {
  fill: currentColor;
  d: path("M3 12a2.5 2.5 0 0 1 2.5 -2.5h13A2.5 2.5 0 0 1 21 12a2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
