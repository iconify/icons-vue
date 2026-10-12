<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9mc9tuxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:growth-plant" /></template>
<style>
.i9mc9tuxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13h8.5q1.25 0 1.25 1.25v1.5q0 1.25.88 1.25q.87 0 .87 1.25V20q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25v-1.75q0-1.25.88-1.25q.87 0 .87-1.25v-1.5Q6.5 13 7.75 13M6.5 17h11M12 12.25V7m0 1.75c0-2.6-1.9-4.5-4.75-4.5c0 2.6 1.9 4.5 4.75 4.5M12 7c0-2.3 1.7-4.25 4.5-4.25C16.5 5.05 14.8 7 12 7");
}

</style>
