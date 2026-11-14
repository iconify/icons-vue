<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4_r0bcji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:catherine-wheel" /></template>
<style>
.t4_r0bcji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12a4.75 4.75 0 0 1 9.5 0M12 12a4.75 4.75 0 0 1 0 9.5m0-9.5a4.75 4.75 0 0 1-9.5 0m9.5 0a4.75 4.75 0 0 1 0-9.5");
}

</style>
