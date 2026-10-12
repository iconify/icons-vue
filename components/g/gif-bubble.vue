<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="of4kfwcob"/><path class="wapa5xd7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gif-bubble" /></template>
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

.wapa5xd7a {
  d: path("M9.5 8.25H8A1.25 1.25 0 0 0 6.75 9.5V12A1.25 1.25 0 0 0 8 13.25h1.5V11h-1M12 8.25v5m5-5h-2.75v5m0-2.5h2.25");
}

</style>
