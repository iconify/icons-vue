<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0ys0--h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cells-under-microscope" /></template>
<style>
.nt0ys0--h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5zA2.5 2.5 0 0 1 14.5 5v3a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 8V5A2.5 2.5 0 0 1 12 2.5m0 8v3m-4 1h8M16 5c4 2 4.5 9 1 13.5M5.5 21h13M4 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m.75 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
