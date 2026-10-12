<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w56m42b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kirpan" /></template>
<style>
.w56m42b7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v5.5m-3.25 0h6.5m-4.75 0h3v7.5c0 2.5-1 4.5-3.25 5.5c.5-1.75.25-3.5.25-5.5Zm0 3.5h3");
}

</style>
