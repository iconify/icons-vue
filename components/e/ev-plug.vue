<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m14tjhb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug" /></template>
<style>
.m14tjhb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5h5.105a2 2 0 0 1 1.574.766a8.485 8.485 0 1 1-13.358 0A2 2 0 0 1 6.895 5ZM8 9h.01M12 9h.01M16 9h.01M10 14h.01M14 14h.01");
}

</style>
