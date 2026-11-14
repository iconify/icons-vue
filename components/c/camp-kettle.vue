<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uop7mdv-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-kettle" /></template>
<style>
.uop7mdv-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 14.5l1.5-6h12l1.5 6Zm1.5-6c0-6 12-6 12 0m-12.75 3L2.75 8M13 17.25c1.75 1.75 1.75 3.5 0 3.5s-1.75-1.75 0-3.5");
}

</style>
