<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us1lxlb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dreidel" /></template>
<style>
.us1lxlb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.172 7.101l7.727 2.071a1.5 1.5 0 0 1 1.061 1.837l-1.031 3.845a1.5 1.5 0 0 1-.549.812l-5.182 3.883a1.5 1.5 0 0 1-2.278-.611l-2.546-5.953a1.5 1.5 0 0 1-.07-.978l1.03-3.845a1.5 1.5 0 0 1 1.838-1.061m5.157-3.794l-1.294 4.829M6.17 12.508l10.625 2.847");
}

</style>
