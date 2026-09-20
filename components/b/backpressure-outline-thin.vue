<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_vuvgsaw"/><path class="bj2hlhbfp"/><path class="ecph9tq5i"/><path class="t3rq50btb"/><path class="fdua8zbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backpressure-outline-thin" /></template>
<style>
.bj2hlhbfp {
  d: path("M3 12h12");
}

.ecph9tq5i {
  d: path("M3 18h12");
}

.f_vuvgsaw {
  d: path("M3 6h12");
}

.fdua8zbmm {
  d: path("m16 7 3 -3 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3rq50btb {
  d: path("M19 4v16");
}

</style>
