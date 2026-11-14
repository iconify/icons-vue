<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="youqy3w_k"/><path class="ox10py_uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grief" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ox10py_uq {
  d: path("M14 6.75a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 1.5 2.5a1.5 1.5 0 0 1-1.5 2.5a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1-1.5-2.5a1.5 1.5 0 0 1 1.5-2.5M7 16c-2.5 0-4-1.5-4-3.5c2.5 0 4 1.5 4 3.5m8.5 0c1.5 2 1.75 2.75 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-.75.25-1.5 1.75-3.5");
}

.youqy3w_k {
  d: path("M7 21.5V11c0-5 2.5-7.5 6-7.5c1.5 0 2.5.75 2.5 1.75");
}

</style>
