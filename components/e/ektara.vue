<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d2m10acnt"/><path class="e1zs40fnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ektara" /></template>
<style>
.d2m10acnt {
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.e1zs40fnj {
  d: path("M12 2.5za1.25 1.25 0 0 1 1.25 1.25v5.5A1.25 1.25 0 0 1 12 10.5a1.25 1.25 0 0 1-1.25-1.25v-5.5A1.25 1.25 0 0 1 12 2.5M13.25 5L17 3m-6.75 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
