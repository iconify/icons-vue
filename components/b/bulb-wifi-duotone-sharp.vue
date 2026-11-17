<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qo27ym3jh"/><path class="de6ikfmhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-wifi-duotone-sharp" /></template>
<style>
.de6ikfmhn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 16v2H6v-2c0-1-2-2.33-2-4a4 4 0 1 1 8 0c0 1.67-2 3-2 4m-4 5h4m3.657-14.657A8 8 0 0 1 16 12m.485-8.485A12 12 0 0 1 20 12");
}

.ft5dv1b6b {
  fill: none;
}

.qo27ym3jh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 18H6v-2c0-1-2-2.33-2-4a4 4 0 0 1 8 0c0 1.67-2 3-2 4Z");
}

</style>
