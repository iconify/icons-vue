<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t501rxv4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-washing-kids" /></template>
<style>
.t501rxv4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H12a3.5 3.5 0 0 1 3.5 3.5V9m-8-6.75V5M5 2.25h5m5.5 9.5v3M12 17.5h7a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

</style>
