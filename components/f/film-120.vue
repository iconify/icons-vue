<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzfnlj_4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-120" /></template>
<style>
.qzfnlj_4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5h6a1.5 1.5 0 0 1 1.5 1.5v11A1.5 1.5 0 0 1 15 19H9a1.5 1.5 0 0 1-1.5-1.5v-11A1.5 1.5 0 0 1 9 5M6.75 2.5h10.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 17.25 5H6.75A1.25 1.25 0 0 1 5.5 3.75A1.25 1.25 0 0 1 6.75 2.5m0 16.5h10.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H6.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 6.75 19M16.5 8H21v8h-4.5");
}

</style>
