<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fq57jobuo"/><path class="dsw8_z0-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-wifi-duotone-round" /></template>
<style>
.dsw8_z0-q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 16v1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1c0-1-2-2.33-2-4a4 4 0 1 1 8 0c0 1.67-2 3-2 4m-4 5h4m3.657-14.657A8 8 0 0 1 16 12m.485-8.485A12 12 0 0 1 20 12");
}

.fq57jobuo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1c0-1-2-2.33-2-4a4 4 0 0 1 8 0c0 1.67-2 3-2 4Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
