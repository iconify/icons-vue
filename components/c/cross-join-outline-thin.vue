<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="aeqgdde5a"/><path class="pd0q9ub5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cross-join-outline-thin" /></template>
<style>
.aeqgdde5a {
  d: path("m7 6 10 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pd0q9ub5m {
  d: path("M17 6 7 16");
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.t3rq50btb {
  d: path("M19 4v16");
}

</style>
