<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgps9rb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lighting-desk" /></template>
<style>
.sgps9rb_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.777 5h10.446a2.625 2.625 0 0 1 2.599 2.254l1.25 8.75A2.625 2.625 0 0 1 18.473 19H5.527a2.625 2.625 0 0 1-2.599-2.996l1.25-8.75A2.625 2.625 0 0 1 6.777 5M7.5 8v8m-1.25-3h2.5M12 8v8m-1.25-6h2.5m3.25-2v8m-1.25-2h2.5");
}

</style>
