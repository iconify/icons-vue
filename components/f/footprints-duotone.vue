<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f99t6na4k"/><path class="aghfg79bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-duotone" /></template>
<style>
.aghfg79bp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1zm18-2V7c0-3-1-4-3-4c-3 0-4 2-4 4c0 3 2 4 2 7v4a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1zM3 17h5m13-2h-5");
}

.f99t6na4k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 18a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-4c0-3-2-4-2-7c0-2 1-4 4-4c2 0 3 1 3 4ZM3 20V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1");
}

.ft5dv1b6b {
  fill: none;
}

</style>
