<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dev6x1e-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:learning-streak" /></template>
<style>
.dev6x1e-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3s6 5.5 6 11a6 6 0 0 1-12 0c0-2.75 1.75-4.5 3-6c0 1.75.75 3 2 3c-.5-2.75 0-5.5 1-8M9.5 21.5h5");
}

</style>
