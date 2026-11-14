<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3dnndbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crayons" /></template>
<style>
.s3dnndbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.5zA1.5 1.5 0 0 1 8 10v8.5A1.5 1.5 0 0 1 6.5 20A1.5 1.5 0 0 1 5 18.5V10a1.5 1.5 0 0 1 1.5-1.5M12 5za1.5 1.5 0 0 1 1.5 1.5v12A1.5 1.5 0 0 1 12 20a1.5 1.5 0 0 1-1.5-1.5v-12A1.5 1.5 0 0 1 12 5m5.5 3.5zA1.5 1.5 0 0 1 19 10v8.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V10a1.5 1.5 0 0 1 1.5-1.5M5 8.5l1.5-3l1.5 3M10.5 5L12 2.5L13.5 5M16 8.5l1.5-3l1.5 3");
}

</style>
