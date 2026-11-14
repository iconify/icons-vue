<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bos0j4biy"/><path class="rf-y9ge8v"/><path class="e8v5ujbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assets-column" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.e8v5ujbec {
  d: path("M15.75 10h1.5A1.75 1.75 0 0 1 19 11.75v7.5A1.75 1.75 0 0 1 17.25 21h-1.5A1.75 1.75 0 0 1 14 19.25v-7.5A1.75 1.75 0 0 1 15.75 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rf-y9ge8v {
  fill: currentColor;
  d: path("M7.75 3h1.5A1.75 1.75 0 0 1 11 4.75v14.5A1.75 1.75 0 0 1 9.25 21h-1.5A1.75 1.75 0 0 1 6 19.25V4.75A1.75 1.75 0 0 1 7.75 3");
}

</style>
