<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sm5itqg7g"/><path class="tbsw0jb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-insurance-limit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sm5itqg7g {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6ZM6.5 7.5H8m1.5 0H11m1.5 0H14m1.5 0H17M6.5 10h11");
}

.tbsw0jb7i {
  d: path("M9.25 12.5h5.5A1.25 1.25 0 0 1 16 13.75A1.25 1.25 0 0 1 14.75 15h-5.5A1.25 1.25 0 0 1 8 13.75a1.25 1.25 0 0 1 1.25-1.25m0 2.5h5.5A1.25 1.25 0 0 1 16 16.25a1.25 1.25 0 0 1-1.25 1.25h-5.5A1.25 1.25 0 0 1 8 16.25A1.25 1.25 0 0 1 9.25 15");
}

</style>
