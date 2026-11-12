<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="absv55cjd"/><path class="v3l_eacmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-union-duotone" /></template>
<style>
.absv55cjd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 2a2 2 0 0 1 2 2v4h4a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H10a2 2 0 0 1-2-2v-4H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.v3l_eacmd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h5a1 1 0 0 1 1 1v4a1 1 0 0 0 1 1h4a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1v-4a1 1 0 0 0-1-1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1z");
}

</style>
