<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq-oetb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heptagon" /></template>
<style>
.kq-oetb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.139 3.548l5.149 2.48a2.63 2.63 0 0 1 1.421 1.781l1.272 5.573a2.63 2.63 0 0 1-.507 2.22l-3.564 4.469a2.63 2.63 0 0 1-2.052.988H9.142a2.63 2.63 0 0 1-2.052-.988l-3.564-4.469a2.63 2.63 0 0 1-.507-2.22l1.272-5.573a2.63 2.63 0 0 1 1.421-1.781l5.149-2.48a2.63 2.63 0 0 1 2.278 0");
}

</style>
