<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuab_hz2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-shop" /></template>
<style>
.tuab_hz2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5L4.5 3h15L21 7.5M4.5 8.75V21m15-12.25V21M3 7.5a4 4 0 0 0 6 0a4 4 0 0 0 6 0a4 4 0 0 0 6 0M12 12a1.75 1.75 0 0 1 2.5 1.5a1.75 1.75 0 0 1 0 3A1.75 1.75 0 0 1 12 18a1.75 1.75 0 0 1-2.5-1.5a1.75 1.75 0 0 1 0-3A1.75 1.75 0 0 1 12 12m0 6v3");
}

</style>
