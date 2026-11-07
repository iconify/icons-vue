<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1_lbm_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-round" /></template>
<style>
.wj1_lbm_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.667 21a2.667 2.667 0 0 1 0-5.333C7 11.667 13 12.333 13 17a2 2 0 1 1 0 4ZM21 9a6 6 0 0 1-3.85 5.601M9 9a6 6 0 0 1 6-6a4.269 4.269 0 1 0 6 6");
}

</style>
