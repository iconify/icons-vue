<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxsny1bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:attic-ladder" /></template>
<style>
.cxsny1bjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h4m12.5 0h2.5m-12 0L5 21M16 3.5L11.5 21M8.25 8.5h6.5M7 13h6.5M6 17.5h6.5m6.5-14V10");
}

</style>
