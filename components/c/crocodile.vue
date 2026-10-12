<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nqizy4bqi"/><path class="i2c8mef7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crocodile" /></template>
<style>
.i2c8mef7s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 10.5h.01");
}

.nqizy4bqi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 11.5l4.5-1c.25-.75.75-1.25 1.5-1.25s1.25.5 1.5 1.25q.75-.75 1.5 0t1.5 0t1.5 0C18 10.5 19.5 12 21 13.75c.1.15 0 .35-.2.35l-4.05.15l1 2c.2.45-.1.75-.5.75h-1.5c-.4 0-.6-.4-.45-.75l.2-.5l-.5-1.5h-4.75l-.5 2c-.1.45-.4.75-.85.75H7.75c-.4 0-.6-.4-.35-.75l1.1-2H8c-1.75-.25-3.25-.5-4.25-.75Q3 13.2 3 12.6c0-.45.25-.95.75-1.1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
