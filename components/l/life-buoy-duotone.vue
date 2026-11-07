<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zcoc9d2yx"/><path class="kt4rzrl9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:life-buoy-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kt4rzrl9i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6a8.485 8.485 0 1 1 12 12A8.485 8.485 0 0 1 6 6m3 3a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6M6 6l3 3m9-3l-3 3m3 9l-3-3m-9 3l3-3");
}

.zcoc9d2yx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.431 3.209c4.855-1.97 10.388.367 12.359 5.222a9.487 9.487 0 0 1-5.222 12.359a9.487 9.487 0 0 1-12.359-5.222c-1.97-4.855.367-10.388 5.222-12.359M15 9a4.244 4.244 0 1 0-6.002 6A4.244 4.244 0 0 0 15 9");
}

</style>
