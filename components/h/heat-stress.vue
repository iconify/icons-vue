<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkuqbtbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-stress" /></template>
<style>
.jkuqbtbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5-7V4M5 9.25h1.75m10.5 0H19m-12-5L8.25 5.5M17 4.25L15.75 5.5M12 21.5V15m0 0c-2.5-.5-4.5 1-4.75 4.5c2.25-.75 4-2.5 4.75-4.5m0 0c2.5-.5 4.5 1 4.75 4.5c-2.25-.75-4-2.5-4.75-4.5");
}

</style>
