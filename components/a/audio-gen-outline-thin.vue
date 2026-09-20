<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="l517yxbln"/><path class="n4e83dijt"/><path class="g6ulbfs0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-gen-outline-thin" /></template>
<style>
.el0n_ccnv {
  d: path("M8 5v14");
}

.g6ulbfs0a {
  d: path("M15 11h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.n4e83dijt {
  d: path("M18 8v6");
}

</style>
