<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ayungmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug-round" /></template>
<style>
.o7ayungmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5h4.015a4 4 0 0 1 3.58 2.216a8.485 8.485 0 1 1-15.19 0A4 4 0 0 1 7.985 5ZM8 9h.01M12 9h.01M16 9h.01M10 14h.01M14 14h.01");
}

</style>
