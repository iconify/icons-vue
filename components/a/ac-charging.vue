<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztcsqe2ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ac-charging" /></template>
<style>
.ztcsqe2ts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5h10v4a5 5 0 0 1-10 0Zm2.5-4v4m5-4v4m-10 13q1.875-3 3.75 0t3.75 0t3.75 0t3.75 0");
}

</style>
