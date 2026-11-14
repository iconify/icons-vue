<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e346cfbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cell-x" /></template>
<style>
.e346cfbdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.704 20.367Q11.88 20.5 11 20.5c-5 0-8.5-3.5-8.5-8.5s3-9.5 7.5-9.5c5.5 0 10.5 3 10.5 8.5q-.001.9-.14 1.744M15.5 15.5l5 5m0-5l-5 5");
}

</style>
