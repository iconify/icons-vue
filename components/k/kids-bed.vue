<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4i4nt1-g"/><path class="c7oxexnqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-bed" /></template>
<style>
.c7oxexnqh {
  d: path("M9.5 10H16v3");
}

.f4i4nt1-g {
  d: path("M3.5 19V8.5a3 3 0 0 1 6 0V13h11v6m-17-2.5h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
