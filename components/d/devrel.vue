<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-g2xdbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:devrel" /></template>
<style>
.j-g2xdbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 21c0-3.75 2.25-6 5-6s5 2.25 5 6M15 7.25h.59a1.5 1.5 0 0 0 .763-.209l2.884-1.704A1.5 1.5 0 0 1 21.5 6.629v4.742a1.5 1.5 0 0 1-2.263 1.292l-2.884-1.704a1.5 1.5 0 0 0-.763-.209H15a1 1 0 0 1-1-1v-1.5a1 1 0 0 1 1-1");
}

</style>
