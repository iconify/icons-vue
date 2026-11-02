<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vrr9p2ble"/><path class="x1nm-9p3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-check-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vrr9p2ble {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12.707 2.293l8 8A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0");
}

.x1nm-9p3k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 7l4 4v10H4V11l8-8zm-7 7l2 2l4-4");
}

</style>
