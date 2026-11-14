<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjlir8r9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:follow-team" /></template>
<style>
.sjlir8r9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 21c0-4 3.25-6.5 7.5-6.5c1.458 0 2.743.278 3.854.717M18 15v6m-3-3h6");
}

</style>
