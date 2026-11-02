<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cqn6vibux"/><path class="ts82lc2hg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-duotone-sharp" /></template>
<style>
.cqn6vibux {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3h6a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m10 2h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.ts82lc2hg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4v16h6V4Zm10 2v12h6V6ZM3 12h18");
}

</style>
