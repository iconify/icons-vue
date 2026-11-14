<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ce8dbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:build-mode" /></template>
<style>
.h0ce8dbwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.5h14.5A1.75 1.75 0 0 1 21 12.25v7.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75v-7.5a1.75 1.75 0 0 1 1.75-1.75M3 14.25h18M3 18h18m-9-7.5v3.75m-4.5 0V18m9-3.75V18M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 5.75v-1.5A1.75 1.75 0 0 1 9.75 2.5");
}

</style>
