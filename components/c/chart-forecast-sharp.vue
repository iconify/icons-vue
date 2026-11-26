<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hd7p6448q"/><path clip-rule="evenodd" class="yysgy_bed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-forecast-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hd7p6448q {
  d: path("M3 2L3 21L22 21M6.7071 17.2929L13.2929 10.7071");
}

.yysgy_bed {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 8C17 8.5523 16.5523 9 16 9C15.4477 9 15 8.5523 15 8C15 7.4477 15.4477 7 16 7C16.5523 7 17 7.4477 17 8ZM20 5C20 5.5523 19.5523 6 19 6C18.4477 6 18 5.5523 18 5C18 4.4477 18.4477 4 19 4C19.5523 4 20 4.4477 20 5Z");
  stroke: none;
}

</style>
