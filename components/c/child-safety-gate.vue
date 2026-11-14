<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnyajynrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:child-safety-gate" /></template>
<style>
.pnyajynrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 4h11.75A2.625 2.625 0 0 1 20.5 6.625v9.75A2.625 2.625 0 0 1 17.875 19H6.125A2.625 2.625 0 0 1 3.5 16.375v-9.75A2.625 2.625 0 0 1 6.125 4M8 4v15m4-15v15m4-15v15");
}

</style>
