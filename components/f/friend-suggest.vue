<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-lnnab2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:friend-suggest" /></template>
<style>
.u-lnnab2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m-3.25 12c0-3.25 3-5.5 7-5.5s7 2.25 7 5.5ZM18.5 2q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3");
}

</style>
