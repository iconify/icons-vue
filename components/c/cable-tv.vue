<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0p4hkbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-tv" /></template>
<style>
.x0p4hkbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7h8a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 14 18H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 7m.5-4L10 7l3.5-4m4 9.5H19a1.5 1.5 0 0 1 1.5 1.5v4.5m0 0zA1.5 1.5 0 0 1 22 20a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 19 20a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
