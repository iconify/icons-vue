<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3yqwb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:asic-miner" /></template>
<style>
.qp3yqwb0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 5.5h4.75A2.625 2.625 0 0 1 17 8.125v4.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 12.875v-4.75A2.625 2.625 0 0 1 9.625 5.5m.375-3v3m4-3v3M4 9h3m-3 3h3m10-3h3m-3 3h3m-10 3.5v5m4-5v5m-11.5 0h19");
}

</style>
