<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsq_v9bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hardwood-floor" /></template>
<style>
.wsq_v9bio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h10l4.5 16h-19Zm3.25 0l-1.5 16m5-16l1.5 16m-11-6h5m.5-5h4.5m.25 3h4.75");
}

</style>
