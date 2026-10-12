<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="slz-7lbmv"/><path class="eecrw4bqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-review" /></template>
<style>
.eecrw4bqw {
  d: path("m9.75 8.25l-2.25 2.5l2.25 2.5m4.5-5l2.25 2.5l-2.25 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.slz-7lbmv {
  d: path("M5.25 3.75h13.5a2.5 2.5 0 0 1 2.5 2.5v9a2.5 2.5 0 0 1-2.5 2.5h-8.5l-3.5 2.9a.75.75 0 0 1-1.25-.58v-2.32a2.5 2.5 0 0 1-2.75-2.5v-9a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
