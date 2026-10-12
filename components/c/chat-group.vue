<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="of4kfwcob"/><path class="yd5mcsbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-group" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.of4kfwcob {
  d: path("M2.75 6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v9a2.5 2.5 0 0 1-2.5 2.5H12.5L8 20.85a.77.77 0 0 1-1.25-.6v-2.5h-1.5a2.5 2.5 0 0 1-2.5-2.5Z");
}

.yd5mcsbuw {
  d: path("M10.75 8.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m5.5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M6.5 14c.3-1.4 1.35-2.25 2.75-2.25S11.7 12.6 12 14m0 0c.3-1.4 1.35-2.25 2.75-2.25s2.45.85 2.75 2.25");
}

</style>
