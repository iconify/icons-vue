<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abn_scb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-growth" /></template>
<style>
.abn_scb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5c2.5-3.25 14.5-3.25 17 0Zm8.5-2.75V10m0 5c-4 0-7-2.5-7-6c4 0 7 2.5 7 6m0-5c0-3.5 3-6 7-6c0 3.5-3 6-7 6");
}

</style>
