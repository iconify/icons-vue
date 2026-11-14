<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8441y2ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-lotion" /></template>
<style>
.u8441y2ux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9h2.5a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 9.5 21H7a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 7 9m.25-2.5h2a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 9.25 9h-2A1.25 1.25 0 0 1 6 7.75A1.25 1.25 0 0 1 7.25 6.5m1 0V4m-2 0h7.5v1.5m2 15c0-2.5 1.75-3 3-5c1.25 2 3 2.5 3 5Z");
}

</style>
