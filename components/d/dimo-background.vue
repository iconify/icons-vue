<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="bu7w1_b0j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dimo-background" /></template>
<style>
.bu7w1_b0j {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.08 7.75c-.855 0-1.58.77-1.58 1.65v8.35H4V9.4c0-1.74 1.38-3.15 3.08-3.15S10 7.66 10 9.4v5.975c0 .45.375.875.96.875c.3 0 .58-.235.715-.515L15.54 7.59a2.35 2.35 0 0 1 2.11-1.34c1.3 0 2.35 1.075 2.35 2.4v9.1h-1.5v-9.1c0-.465-.4-.9-.85-.9c-.315 0-.6.24-.74.53l-3.865 8.15a2.32 2.32 0 0 1-2.085 1.32c-1.285 0-2.46-1.06-2.46-2.375V9.4c0-.88-.56-1.65-1.42-1.65");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
