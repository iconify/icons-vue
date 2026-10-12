<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujp1ribjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ceiling-fan" /></template>
<style>
.ujp1ribjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v4.5m-2 0h4a1.5 1.5 0 0 1 1.5 1.5V9h4.75a1 1 0 0 1 1 1v.5a1 1 0 0 1-1 1H15.5v.25a1.5 1.5 0 0 1-1.5 1.5h-4a1.5 1.5 0 0 1-1.5-1.5v-.25H3.75a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1H8.5v-.25a1.5 1.5 0 0 1 1.5-1.5m-1 8.5h6a3 3 0 0 1-6 0");
}

</style>
