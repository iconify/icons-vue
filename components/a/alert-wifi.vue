<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnbq3ugsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alert-wifi" /></template>
<style>
.cnbq3ugsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 19.5h.01m-2.838-2.828a4 4 0 0 1 5.656 0m-8.181-3.117a8 8 0 0 1 10.706 0M2.617 9.67a12 12 0 0 1 13.766 0M20.5 8v6m0 4.5h.01");
}

</style>
