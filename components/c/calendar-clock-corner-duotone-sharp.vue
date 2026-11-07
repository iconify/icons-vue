<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x3sp62bgi"/><path class="bkg8p1fey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner-duotone-sharp" /></template>
<style>
.bkg8p1fey {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16m-9 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

.ft5dv1b6b {
  fill: none;
}

.x3sp62bgi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 9V5a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1");
}

</style>
