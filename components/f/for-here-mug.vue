<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm1p4tjil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:for-here-mug" /></template>
<style>
.qm1p4tjil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4h10v9q0 4-4 4h-2q-4 0-4-4Zm10 3h1a2.5 2.5 0 0 1 0 5h-1m-14 5h19Q20 20.5 12 20.5T2.5 17");
}

</style>
