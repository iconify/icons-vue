<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zb0hc8b5e"/><path class="infvveb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-check-done" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.infvveb4y {
  d: path("m16.25 18l1.25 1.25l2.25-2.5");
}

.zb0hc8b5e {
  d: path("M3 2.5v3.75C3 8.25 4.75 10 6.75 10s3.75-1.75 3.75-3.75V2.5M6.75 10v2.5a4.48 4.48 0 0 0 4.722 4.495m4.278-5.206V11M13.5 8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m.75 9.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
