<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7__jb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kuiper-belt" /></template>
<style>
.hv7__jb0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11.5 0h.01m-2.76 3.5h.01M12 17h.01m-6.76-1.5h.01M2.5 12h.01m2.74-3.5h.01M12 7h.01m6.74 1.5h.01");
}

</style>
