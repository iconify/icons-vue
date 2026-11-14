<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e96yj_bnh"/><path class="m6zkc_wxa"/><path class="opi40eghl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cobrowse" /></template>
<style>
.e96yj_bnh {
  d: path("M6.5 16.5h-2a2 2 0 0 1-2-2v-10a2 2 0 0 1 2-2H15a2 2 0 0 1 2 2v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6zkc_wxa {
  d: path("M10 6.5h8a3.5 3.5 0 0 1 3.5 3.5v7.5A3.5 3.5 0 0 1 18 21h-8a3.5 3.5 0 0 1-3.5-3.5V10A3.5 3.5 0 0 1 10 6.5M6.5 10h15");
}

.opi40eghl {
  d: path("m13.712 13.736l1.523.554a.514.514 0 0 1 .015.96l-.72.288a1.5 1.5 0 0 0-.785.722l-.37.74a.568.568 0 0 1-1.049-.082l-.451-1.418a1.419 1.419 0 0 1 1.837-1.764");
}

</style>
