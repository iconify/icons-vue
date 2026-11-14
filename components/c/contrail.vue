<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u_m9chb8x"/><path class="jed1n_btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contrail" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jed1n_btf {
  d: path("M13.75 10.75Q7 13 3 20.5");
}

.u_m9chb8x {
  d: path("m20.359 4.848l-.088.439a1.5 1.5 0 0 1-.41.766l-.901.901a1.5 1.5 0 0 0-.419 1.307l.498 2.988a.97.97 0 0 1-.271.847a.377.377 0 0 1-.597-.083l-1.039-1.871a.754.754 0 0 0-1.193-.167l-.267.268a1.5 1.5 0 0 0-.44 1.06v.44a.321.321 0 0 1-.588.178l-.66-.989a1.5 1.5 0 0 0-.416-.416l-.989-.66a.321.321 0 0 1 .178-.588h.44a1.5 1.5 0 0 0 1.06-.44l.268-.267a.754.754 0 0 0-.167-1.193l-1.871-1.039a.377.377 0 0 1-.083-.597a.97.97 0 0 1 .847-.271l2.988.498a1.5 1.5 0 0 0 1.307-.419l.901-.901a1.5 1.5 0 0 1 .766-.41l.439-.088a.6.6 0 0 1 .707.707");
}

</style>
