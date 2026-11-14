<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2z3iybjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gated-community" /></template>
<style>
.n2z3iybjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5H5A1.5 1.5 0 0 1 6.5 9v11A1.5 1.5 0 0 1 5 21.5h-.5A1.5 1.5 0 0 1 3 20V9a1.5 1.5 0 0 1 1.5-1.5M8 9h12a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 12H8a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 8 9m2.5 0l-1 3M14 9l-1 3m4.5-3l-1 3m-1.773 5.555l2.25-2.1a1.5 1.5 0 0 1 2.046 0l2.25 2.1a1.5 1.5 0 0 1 .477 1.097v1.598a1.5 1.5 0 0 1-1.5 1.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-1.598a1.5 1.5 0 0 1 .477-1.097");
}

</style>
