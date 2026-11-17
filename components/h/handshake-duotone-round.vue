<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_vqw_ivz"/><path class="y_i7z7pwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handshake-duotone-round" /></template>
<style>
.b_vqw_ivz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5h7c2-2 5-2 7-1l2 1h2v7l-2 2a2.122 2.122 0 0 1-3 3l-1-1l-.379.5A2.122 2.122 0 0 1 11 18l-1-1l-.379.5A2.122 2.122 0 0 1 6 19l-3-3Z");
}

.ft5dv1b6b {
  fill: none;
}

.y_i7z7pwq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5c2-2 5-2 7-1l2 1h2m0-1v8l-2 2m-9-9L7 8a2.121 2.121 0 1 0 3 3l1-1a2.83 2.83 0 0 1 4 0l4 4a2.121 2.121 0 1 1-3 3l-3-3M3 4v12l3 3a2.121 2.121 0 1 0 3-3l2 2a2.121 2.121 0 1 0 3-3M3 5h7");
}

</style>
