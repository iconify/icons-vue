<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y92o6zafv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bpm-counter" /></template>
<style>
.y92o6zafv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.84 2.5h2.32a1.75 1.75 0 0 1 1.69 1.293l4.054 15A1.75 1.75 0 0 1 17.214 21H6.786a1.75 1.75 0 0 1-1.69-2.207l4.054-15A1.75 1.75 0 0 1 10.84 2.5M5.5 17h13M12 17l6-12");
}

</style>
