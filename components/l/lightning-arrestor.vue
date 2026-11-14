<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnax5wx0c"/><path class="j6f1c3fkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightning-arrestor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6f1c3fkv {
  d: path("M13 8.5L11 12h2l-2 3.5");
}

.rnax5wx0c {
  d: path("M10.625 6.5h2.75A2.625 2.625 0 0 1 16 9.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 8 14.875v-5.75A2.625 2.625 0 0 1 10.625 6.5M12 2.5v4m0 11v4");
}

</style>
