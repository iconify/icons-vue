<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux2hmyfnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hr-department" /></template>
<style>
.ux2hmyfnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5c-4.75-2.75-6.5-5-6.5-6.75c0-1.5 1.25-2.25 2.75-2.25s3 .75 3.75 2c.75-1.25 2.25-2 3.75-2s2.75.75 2.75 2.25c0 1.75-1.75 4-6.5 6.75M3.25 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-.75 6a2.25 1.75 0 0 1 4.5 0m3.5-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-.75 6a2.25 1.75 0 0 1 4.5 0m3.5-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-.75 6a2.25 1.75 0 0 1 4.5 0");
}

</style>
