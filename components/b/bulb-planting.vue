<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mklebkbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bulb-planting" /></template>
<style>
.mklebkbsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11c2 2 6 3.5 6 6.5c0 2.5-2.5 4-6 4s-6-1.5-6-4c0-3 4-4.5 6-6.5M2.5 8h19M12 11V2.5M12 5c.5-1.75 2.5-2.5 4.5-2.5C16 4.25 14 5 12 5");
}

</style>
