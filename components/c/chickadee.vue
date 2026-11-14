<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aza3-sbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chickadee" /></template>
<style>
.aza3-sbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 9.5l-2.5-1l2.75-1.25C7 4.5 11.5 3.5 14 5.5s3 5 2.75 7l3.5 5.5l-2.25.75l-3.5-3c-3.5 1.75-8.25.25-8.5-4Zm-3 10h10.5M9 8h.01m1.49 8.75v2.75");
}

</style>
