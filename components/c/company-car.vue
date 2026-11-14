<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhxqpc3wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:company-car" /></template>
<style>
.lhxqpc3wl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 10.5l1.25-4c.25-.9 1-1.5 2-1.5h6.5c1 0 1.75.6 2 1.5l1.25 4m-12.25 0h11.5A3.25 3.25 0 0 1 21 13.75A3.25 3.25 0 0 1 17.75 17H6.25A3.25 3.25 0 0 1 3 13.75a3.25 3.25 0 0 1 3.25-3.25M6 17v2.5M18 17v2.5M6.75 13.75h.01m10.49 0h.01M10.5 14h3");
}

</style>
