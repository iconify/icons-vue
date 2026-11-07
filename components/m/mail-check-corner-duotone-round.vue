<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wbhuuubtm"/><path class="q4l8y57bw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q4l8y57bw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2M4 7l3 3c.64.64 1.72 1 3 1h4c1.28 0 2.36-.36 3-1l3-3m-5 11l2 2l4-4");
}

.wbhuuubtm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 17.998V19a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v2a1 1 0 0 1-1 1h-6c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15Z");
}

</style>
