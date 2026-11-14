<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg6e3-7fu"/><path class="gvlqjbcnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deck-review" /></template>
<style>
.gvlqjbcnf {
  d: path("M6.5 10L10 6.5l3 2l4.5-3m-2.75 13a3.75 3.75 0 0 1 7 0a3.75 3.75 0 0 1-7 0m3.5 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg6e3-7fu {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v3.75a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5m2.5 19l3.5-4v-4.25m0 4.25v.9m0 .2v2.9");
}

</style>
