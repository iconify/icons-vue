<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gi44n9bvc"/><path class="c16w6-hiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:completion-certificate" /></template>
<style>
.c16w6-hiw {
  d: path("m7 10l3 3l5.5-5.5");
}

.gi44n9bvc {
  d: path("M5.875 3.5h12.25a2.625 2.625 0 0 1 2.625 2.625v7.75a2.625 2.625 0 0 1-2.625 2.625H5.875a2.625 2.625 0 0 1-2.625-2.625v-7.75A2.625 2.625 0 0 1 5.875 3.5m8.625 13v5l1.75-1.25L18 21.5v-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
