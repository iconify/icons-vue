<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d2ifryb6c"/><path class="lz_3gvb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-stamp" /></template>
<style>
.d2ifryb6c {
  d: path("M9.25 6.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lz_3gvb7x {
  d: path("M11.75 9.5h.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m-5 4h10.5A1.75 1.75 0 0 1 19 15.25A1.75 1.75 0 0 1 17.25 17H6.75A1.75 1.75 0 0 1 5 15.25a1.75 1.75 0 0 1 1.75-1.75M3 20h18");
}

</style>
