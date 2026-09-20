<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt0pn2q8p"/><path class="p2xzsobqz"/><path class="u7jotynzh"/><path class="mwsvi3abz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ash-cloud-duotone-regular" /></template>
<style>
.kt0pn2q8p {
  fill: currentColor;
  d: path("M4 12a3.5 3.5 0 0 1 2 -6.5 4.5 4.5 0 0 1 8.5 -1A5 5 0 0 1 18 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mwsvi3abz {
  d: path("m5 21 7 -7 7 7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2xzsobqz {
  fill: currentColor;
  d: path("m5 21 7 -7 7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u7jotynzh {
  d: path("M4 12a3.5 3.5 0 0 1 2 -6.5 4.5 4.5 0 0 1 8.5 -1A5 5 0 0 1 18 12Z");
}

</style>
