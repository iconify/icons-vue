<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0dfddaem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-crack-sharp" /></template>
<style>
.w0dfddaem {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.6175 11.1476L2 10.8473L12 2.9975L22 10.8473L22.3825 11.1476M4 9.2808L4 21L20 21L20 9.2808M12 3L10.5 7.5L13.5 10L10.5 14L13.5 17L12 21");
}

</style>
