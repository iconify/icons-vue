<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ev6hne2rc"/><path class="dwufldtlq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gauze-pad" /></template>
<style>
.dwufldtlq {
  d: path("m20.5 14.5l-5 1l-1 5m-5-17v17m-6-11h17m-5.5-6v6");
}

.ev6hne2rc {
  d: path("M5.5 3.5h13c1.1 0 2 .9 2 2v9l-6 6h-9c-1.1 0-2-.9-2-2v-13c0-1.1.9-2 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
