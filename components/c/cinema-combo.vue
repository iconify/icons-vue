<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lr5m9jbfp"/><path class="nek82ixtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-combo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr5m9jbfp {
  d: path("M4.416 10h4.668a1.75 1.75 0 0 1 1.743 1.908l-.682 7.5A1.75 1.75 0 0 1 8.402 21H5.098a1.75 1.75 0 0 1-1.743-1.592l-.682-7.5A1.75 1.75 0 0 1 4.416 10");
}

.nek82ixtw {
  d: path("M2.5 10c0-3 2.5-4 4.25-2.75C8.5 6 11 7 11 10m4.902-1h3.196a1.75 1.75 0 0 1 1.744 1.895l-.708 8.5A1.75 1.75 0 0 1 18.39 21h-1.78a1.75 1.75 0 0 1-1.744-1.605l-.708-8.5A1.75 1.75 0 0 1 15.902 9M17.5 9L19 3.5");
}

</style>
