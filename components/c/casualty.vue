<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_t5mzb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:casualty" /></template>
<style>
.p_t5mzb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12.25 9h7.25a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-7.25a2 2 0 0 1-2-2a2 2 0 0 1 2-2M2.5 15.75h19");
}

</style>
