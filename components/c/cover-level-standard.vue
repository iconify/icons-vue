<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3p70n6fq"/><path class="ggn3ddcib"/><path class="i499hps_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cover-level-standard" /></template>
<style>
.ggn3ddcib {
  fill: currentColor;
  d: path("M11.75 9.5h.75a1.75 1.75 0 0 1 1.75 1.75v8A1.75 1.75 0 0 1 12.5 21h-.75A1.75 1.75 0 0 1 10 19.25v-8a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i499hps_e {
  d: path("M18.75 3.5h.75a1.75 1.75 0 0 1 1.75 1.75v14A1.75 1.75 0 0 1 19.5 21h-.75A1.75 1.75 0 0 1 17 19.25v-14a1.75 1.75 0 0 1 1.75-1.75");
}

.z3p70n6fq {
  d: path("M4.75 15h.75a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 5.5 21h-.75A1.75 1.75 0 0 1 3 19.25v-2.5A1.75 1.75 0 0 1 4.75 15");
}

</style>
