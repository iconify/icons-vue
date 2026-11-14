<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy5z1dbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customer-churn-risk" /></template>
<style>
.vy5z1dbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0M15.028 19H2.5c0-3.25 2.75-5.5 6.5-5.5c1.699 0 3.193.462 4.319 1.269M16 15.5l5.5 5.5m0-4.5V21H17");
}

</style>
