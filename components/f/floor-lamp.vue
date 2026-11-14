<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxt_y765a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-lamp" /></template>
<style>
.bxt_y765a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.261 3h5.478a1.75 1.75 0 0 1 1.66 1.197l.833 2.5A1.75 1.75 0 0 1 15.572 9H8.428a1.75 1.75 0 0 1-1.66-2.303l.833-2.5A1.75 1.75 0 0 1 9.261 3M12 9v12m-4 0h8");
}

</style>
