<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b3uk5nbqo"/><path class="y_i7z7pwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handshake-duotone-round" /></template>
<style>
.b3uk5nbqo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.605 4c1.614-1.418 3.827-1.916 5.92-1.53c.667.12 1.315.334 1.922.636L19.236 4H21a1 1 0 0 1 1 1v7c0 .265-.105.52-.293.707l-1.409 1.409a3.121 3.121 0 0 1-4.944 3.65a3.123 3.123 0 0 1-5 1a3.12 3.12 0 0 1-5.061.941l-3-3A1 1 0 0 1 2 16V5a1 1 0 0 1 1-1Z");
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
