<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqa473b3v"/><path class="w5g80id2b"/><path class="u31rq4b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crime-rate" /></template>
<style>
.eqa473b3v {
  d: path("M2.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m11 2.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u31rq4b2f {
  d: path("M11 8.25a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0m4 13.25V19m3 2.5v-5m3 5v-7");
}

.w5g80id2b {
  d: path("M9.25 7.5a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0");
}

</style>
