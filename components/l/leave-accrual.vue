<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss1l4ac3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leave-accrual" /></template>
<style>
.ss1l4ac3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V11M8 21.5h8M12 16q-3.5.75-7-3q3.75-1 7 3m0-2q3.5.75 7-3.5q-3.75-1-7 3.5M2.25 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 0h.01M16.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M19 5h.01");
}

</style>
