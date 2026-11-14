<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvgu1zqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-subject-request" /></template>
<style>
.yvgu1zqei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1 10c0-3 1.5-4.5 3.5-4.5S9 15.5 9 18.5M16 5h3l2.5 2.5V19H16Zm-6 7h3.25m-2-2l2 2l-2 2");
}

</style>
