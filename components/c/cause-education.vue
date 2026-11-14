<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on7mpobst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cause-education" /></template>
<style>
.on7mpobst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5c-2-1.5-5.5-2-9.5-1.5v7c4-.5 7.5 0 9.5 1.5Zm0 0c2-1.5 5.5-2 9.5-1.5v7c-4-.5-7.5 0-9.5 1.5ZM7.745 4.096l3.728-1.398a1.5 1.5 0 0 1 1.054 0l3.728 1.398a1.5 1.5 0 0 1 0 2.808l-3.728 1.398a1.5 1.5 0 0 1-1.054 0L7.745 6.904a1.5 1.5 0 0 1 0-2.808M20 5.5V9");
}

</style>
