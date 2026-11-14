<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="c152jbcja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-psd" /></template>
<style>
.c152jbcja {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-6.829 2.835l1.579.79a1.258 1.258 0 0 1 0 2.25l-1.579.79a1.5 1.5 0 0 1-1.342 0l-1.579-.79a1.258 1.258 0 0 1 0-2.25l1.579-.79a1.5 1.5 0 0 1 1.342 0M7.5 16.5l4.5 2.25l4.5-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
