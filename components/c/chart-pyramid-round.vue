<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx8_y6bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-round" /></template>
<style>
.jx8_y6bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 11l3 6c.919 1.838-.162 4-2 4H7c-1.838 0-2.919-2.162-2-4l5-10c.824-1.648 3.176-1.648 4 0zM9 9h6m-9 6h12");
}

</style>
