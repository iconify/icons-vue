<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze6_fbbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ab-wheel" /></template>
<style>
.ze6_fbbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5zA2.5 2.5 0 0 1 14.5 7v10a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 17V7A2.5 2.5 0 0 1 12 4.5M2.5 12h7m5 0h7");
}

</style>
