<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="bohozf9ne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-css" /></template>
<style>
.bohozf9ne {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M10 11.25h-.5a1 1 0 0 0-1 1V14l-1 1l1 1v1.75a1 1 0 0 0 1 1h.5m4-7.5h.5a1 1 0 0 1 1 1V14l1 1l-1 1v1.75a1 1 0 0 1-1 1H14");
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
