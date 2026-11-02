<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hd41erbwa"/><path class="i0-sbmbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hd41erbwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 3v14h-4v4l-2-2l-2 2v-4H3V3Zm-4 14v-2h-4v2Z");
}

.i0-sbmbaz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H3V3h18v14M7 7h10M7 11h2m4 4a2.828 2.828 0 1 1 4-4a2.828 2.828 0 0 1-4 4m0 0v6l2-2l2 2v-6");
}

</style>
