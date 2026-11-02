<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e6f57kg6n"/><path class="bxg479biu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:charging-station-duotone-sharp" /></template>
<style>
.bxg479biu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h10v18H3Zm10 9h4v5h4V7l-3-3M9 8l-3 4h4l-3 4");
}

.e6f57kg6n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h10v18H3Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
