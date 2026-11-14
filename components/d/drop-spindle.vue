<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obqxe0b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drop-spindle" /></template>
<style>
.obqxe0b8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m0-17c5.5 2 5.5 6 0 8c-5.5-2-5.5-6 0-8M5 18a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0");
}

</style>
