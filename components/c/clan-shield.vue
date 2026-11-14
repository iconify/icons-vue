<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zow-mge_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clan-shield" /></template>
<style>
.zow-mge_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9h15v4c0 4-3.5 6.75-7.5 8.5C8 19.75 4.5 17 4.5 13ZM8 9l-.5-5.5L10 6l2-3l2 3l2.5-2.5L16 9");
}

</style>
