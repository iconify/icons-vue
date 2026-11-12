<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qrj6xhmdf"/><path class="m4l6isv0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-pin-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m4l6isv0q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5l2 2m3 7h4v3l1 1c.369.369-.262 1-1 1h-4c-.738 0-1.369-.631-1-1l1-1zm-1 0h6m-3 5v3");
}

.qrj6xhmdf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293M15 13h4v3l1 1c.369.369-.262 1-1 1h-4c-.738 0-1.369-.631-1-1l1-1Z");
}

</style>
