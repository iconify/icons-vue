<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpejcybhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-big-down-line" /></template>
<style>
.vpejcybhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 3.5H9m1.453 15.953l-4.039-4.039A.828.828 0 0 1 7 14a2 2 0 0 0 2-2v-1.812A2.19 2.19 0 0 1 11.188 8h1.625A2.19 2.19 0 0 1 15 10.188V12a2 2 0 0 0 2 2a.828.828 0 0 1 .586 1.414l-4.039 4.039a2.19 2.19 0 0 1-3.094 0");
}

</style>
