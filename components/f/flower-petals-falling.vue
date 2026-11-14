<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyi6khimk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-petals-falling" /></template>
<style>
.nyi6khimk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 5.25a2.25 2.25 0 0 1 0 4.5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1 0-4.5a2.25 2.25 0 0 1 4.5 0M8 12v9.5m0-14h.01M15.5 9q3.5.5 2.5 4q-3-1-2.5-4m2 6.75q3.5.5 2.5 4q-3-1-2.5-4m-5 2q3.5.5 2.5 4q-3-1-2.5-4");
}

</style>
