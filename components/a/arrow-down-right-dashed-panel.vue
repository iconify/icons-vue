<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2w919zsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-right-dashed-panel" /></template>
<style>
.l2w919zsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.34315 4.34315 3 6 3M10.5 3H13.5M21 7V6.00026C21 4.34341 19.6569 3 18 3M7 21H6C4.34315 21 3 19.6569 3 18M3 10.5V13.5M11.5 21H20.5C20.7761 21 21 20.7761 21 20.5V11.5M11.5 11.5L20.5 20.5");
}

</style>
