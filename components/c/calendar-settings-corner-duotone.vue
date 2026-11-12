<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uptghcb8d"/><path class="h24v-4fon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-settings-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h24v-4fon {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2M8 3v2m8-2v2M4 9h16m-6 8a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-3v-1m2.598 2.5l.866-.5m-.866 3.5l.866.5M17 20v1m-2.598-2.5l-.866.5m.866-3.5l-.866-.5");
}

.uptghcb8d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 9a2 2 0 0 0-2 2v10H6a2 2 0 0 1-2-2V9Z");
}

</style>
