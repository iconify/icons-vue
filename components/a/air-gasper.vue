<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp2-rjb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-gasper" /></template>
<style>
.bp2-rjb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V5m-6 6a6 6 0 0 1 12 0Zm2 2.75q-1 2 0 4t0 3.75m4-7.75q-1 2 0 4t0 3.75m4-7.75q-1 2 0 4t0 3.75");
}

</style>
