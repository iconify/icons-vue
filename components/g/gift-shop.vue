<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1gxwy2ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-shop" /></template>
<style>
.v1gxwy2ga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.726 3h12.548a1.75 1.75 0 0 1 1.645 1.152l.727 2A1.75 1.75 0 0 1 19.002 8.5H4.998a1.75 1.75 0 0 1-1.644-2.348l.727-2A1.75 1.75 0 0 1 5.726 3M4 8.5v13h8.5m7.5-8.4V8.5M9.5 3l-.75 5.5M14.5 3l.75 5.5m1.25 9H20a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-3.5A1.5 1.5 0 0 1 15 20v-1a1.5 1.5 0 0 1 1.5-1.5m1.75 0v4m0-4c-1.75-3-3.5-.75 0 0c3.5-.75 1.75-3 0 0");
}

</style>
