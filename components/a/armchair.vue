<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gf_s4_b8u"/><path class="u2mf_tb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:armchair" /></template>
<style>
.gf_s4_b8u {
  d: path("M7 12.5v-6a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u2mf_tb_m {
  d: path("M3 19v-6.5a2 2 0 0 1 4 0V15h10v-2.5a2 2 0 0 1 4 0V19Zm2 0v2m14-2v2");
}

</style>
