<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="btuoimhzm"/><path class="gwf5edc8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:certified-seed" /></template>
<style>
.btuoimhzm {
  d: path("M4.5 10a5 7.5 0 1 0 10 0a5 7.5 0 1 0-10 0");
}

.gwf5edc8z {
  d: path("M9.5 5.75C8 8.5 8 11.5 9.5 14.25M14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
