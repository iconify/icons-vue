<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="nilwmgbzk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nilwmgbzk {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.93 10.735l4.885-4.88L15.965 4L12 7.96L8.045 4l-1.85 1.85l4.88 4.885a1.304 1.304 0 0 0 1.855 0m7.07 5.22l-3.955-3.96l3.95-3.955l-1.85-1.85l-4.88 4.88a1.31 1.31 0 0 0-.285 1.426c.066.158.163.303.285.424l4.88 4.885zm-8 .085L15.95 20l1.855-1.85l-4.88-4.885a1.31 1.31 0 0 0-1.43-.285q-.24.1-.425.285l-4.885 4.88L8.035 20zm-1.265-3.11a1.31 1.31 0 0 0 0-1.85l-4.88-4.885L4 8.045l3.96 3.96L4 15.96l1.85 1.85z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
