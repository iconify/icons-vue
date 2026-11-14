<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sht--bb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dictionary-open" /></template>
<style>
.sht--bb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c-2-1.5-5-2-9.5-1.5V19c4.5-.5 7.5 0 9.5 1.5c2-1.5 5-2 9.5-1.5V4.5C17 4 14 4.5 12 6m0 0v14.5M5.5 10l3.5.25m6 0l3.5-.25");
}

</style>
