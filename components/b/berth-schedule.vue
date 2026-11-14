<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y92z8vf6y"/><path class="e1lau-y5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:berth-schedule" /></template>
<style>
.e1lau-y5o {
  d: path("M16 14.5h4v3.25h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y92z8vf6y {
  d: path("M12.3 19.5H2.5V4H19v7.7M2.5 8.5H19m-12-6v3m7.5-3v3m0 12.25h7l-2 3.25h-3Z");
}

</style>
