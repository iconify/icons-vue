<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf-440yai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-smoke" /></template>
<style>
.wf-440yai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 8.5l3 2.5h13l3-2.5M5.5 11v10h13V11m-10-2.75c-1-1.75 1-3.25 0-5.75M12 8.25C11 6.5 13 5 12 2.5m3.5 5.75c-1-1.75 1-3.25 0-5.75");
}

</style>
