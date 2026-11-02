<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvdw0obcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frame-round" /></template>
<style>
.uvdw0obcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7h10v10H7ZM3 7h4m10 0h4M3 17h4m10 0h4M7 3v4m10-4v4M7 17v4m10-4v4");
}

</style>
