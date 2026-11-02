<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u5_3wcslz"/><path class="gv8qhabdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gv8qhabdg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17c-1.425.797-3.297 1-5 1a9.75 9.75 0 0 1-9-6c.859-2.061 2.132-3.955 4-5m5-1a9.75 9.75 0 0 1 9 6c-.288.69-.576 1.408-1 2m-9-3c-.362.362-1 .448-1 1a2 2 0 0 0 2 2c.552 0 .638-.638 1-1M2 2l20 20");
}

.u5_3wcslz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.721 8.892a10.75 10.75 0 0 1 18.202 2.723a1 1 0 0 1 0 .77a10.751 10.751 0 0 1-19.846 0a1 1 0 0 1 0-.77c.409-.984.963-1.903 1.644-2.723");
}

</style>
