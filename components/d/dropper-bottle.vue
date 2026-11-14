<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzmsadc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dropper-bottle" /></template>
<style>
.lzmsadc9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5V5.25a2 2 0 0 1 4 0V7.5m-3.5 0h3A1.5 1.5 0 0 1 11 9a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 5 9a1.5 1.5 0 0 1 1.5-1.5m-.5 3h4a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4A3.5 3.5 0 0 1 6 10.5m13 3c.75 1 2.5 3 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.5 1.75-3.5 2.5-4.5");
}

</style>
