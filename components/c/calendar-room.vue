<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8me61j8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-room" /></template>
<style>
.x8me61j8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 18H2.5V4h15v7.2m-15-2.7h15m-11-6v3m7-3v3m2 16V15a1 1 0 0 1 1-1H20a1 1 0 0 1 1 1v6.5m-6.5 0H22M18.5 18h.01");
}

</style>
