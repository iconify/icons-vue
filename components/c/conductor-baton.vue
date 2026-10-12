<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmro_kbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conductor-baton" /></template>
<style>
.xmro_kbfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.31 20.69a2.75 1.6-45 1 0 3.88-3.88a2.75 1.6-45 1 0-3.88 3.88m3.94-3.94L19 5m2 4.5c.5 5-3.5 10.5-9.5 11");
}

</style>
