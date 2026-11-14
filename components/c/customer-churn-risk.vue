<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0h92abub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-churn-risk" /></template>
<style>
.h0h92abub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM14.228 19H2.5c0-3.25 2.75-5.5 6.5-5.5c1.539 0 2.91.379 3.992 1.051M16 15.5l5.5 5.5m0-4.5V21H17");
}

</style>
