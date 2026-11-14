<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_vexl-nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campfire-logs" /></template>
<style>
.t_vexl-nh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.5c-2.5 0-4.25-1.75-4.25-4c0-2.5 2.25-4 3.25-8q2.25 2.25 2.25 4.5c.75-.5 1.25-1.25 1.5-2c1 1.25 1.5 3.5 1.5 5.5c0 2.25-1.75 4-4.25 4m-8 1l16 4m-16 0l16-4");
}

</style>
