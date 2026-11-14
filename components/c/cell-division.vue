<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="arcyxdx5y"/><path class="lxtaqtb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cell-division" /></template>
<style>
.arcyxdx5y {
  d: path("M12 9.25C10.75 7 9 6 7 6c-2.75 0-4.5 2.75-4.5 6s1.75 6 4.5 6c2 0 3.75-1 5-3.25C13.25 17 15 18 17 18c2.75 0 4.5-2.75 4.5-6S19.75 6 17 6c-2 0-3.75 1-5 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxtaqtb6z {
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
