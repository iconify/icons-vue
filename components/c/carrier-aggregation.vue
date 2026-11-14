<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t405s5-hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carrier-aggregation" /></template>
<style>
.t405s5-hk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5c4.5 0 4.5 7 9 7m-9 7c4.5 0 4.5-7 9-7m0 0c1.5-4.5 3.5-4.5 5 0s3.5 4.5 5 0");
}

</style>
