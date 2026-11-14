<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbsq0lgrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-zone" /></template>
<style>
.fbsq0lgrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5V3h3m4 0h5m4 0h3v3.5m0 3.5v4m0 3.5V21h-3m-4 0h-5m-4 0h-3v-3.5m0-3.5v-4m11.023-1.305l3.501 6.194a1.75 1.75 0 0 1-1.523 2.611H8.499a1.75 1.75 0 0 1-1.523-2.611l3.501-6.194a1.75 1.75 0 0 1 3.046 0M12 10.25V13m0 2.25h.01");
}

</style>
