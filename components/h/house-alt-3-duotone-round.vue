<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y0drz9yih"/><path class="fk8vhmj5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-3-duotone-round" /></template>
<style>
.fk8vhmj5m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 11l6.343-5.638a4 4 0 0 1 5.314 0L21 11m-2-1.778V17a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9.222");
}

.ft5dv1b6b {
  fill: none;
}

.y0drz9yih {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m21 11l-.013.015L19 9.249V17a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9.249l-1.987 1.766L3 11l6.343-5.638a4 4 0 0 1 5.314 0Z");
}

</style>
