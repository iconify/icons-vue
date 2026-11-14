<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxhxmkfww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-auction" /></template>
<style>
.nxhxmkfww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.793 3.611l4.596 4.596a1.75 1.75 0 0 1 0 2.475l-.707.707a1.75 1.75 0 0 1-2.475 0L6.611 6.793a1.75 1.75 0 0 1 0-2.475l.707-.707a1.75 1.75 0 0 1 2.475 0M8.75 9.25L3 15m10.75 3c1.75-3.5 4.5-3.5 5.75 0l2.5-2.75v5.5L19.5 18c-1.25 3.5-4 3.5-5.75 0");
}

</style>
