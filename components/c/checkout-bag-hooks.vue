<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aa4mcj76t"/><path class="kftlajbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-bag-hooks" /></template>
<style>
.aa4mcj76t {
  d: path("M2.5 4h19M4 4v4.5a1.75 1.75 0 0 0 3.5 0v-1M11 4v4.5a1.75 1.75 0 0 0 3.5 0v-1M18 4v4.5a1.75 1.75 0 0 0 3.5 0v-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kftlajbcn {
  d: path("m5.75 10.25l-2 7.25a2 2 0 0 0 4 0Zm7 0l-2 7.25a2 2 0 0 0 4 0Zm7 0l-2 7.25a2 2 0 0 0 4 0Z");
}

</style>
