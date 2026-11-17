<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gm9g3pijh"/><path class="coq9dz4si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:excavator-duotone-sharp" /></template>
<style>
.coq9dz4si {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m3-2V8h3l4 4v4m-7-4h6m1 1l3-8l5 5v5h-2l-1-2");
}

.ft5dv1b6b {
  fill: none;
}

.gm9g3pijh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 16V8h3l4 4v4a2 2 0 1 1 0 4H5a2 2 0 1 1 0-4Z");
}

</style>
