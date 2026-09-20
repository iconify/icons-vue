<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w8a4-ib_b"/><path class="p0x-f5bdp"/><path class="xptqu8bzs"/><path class="zhn1ajhpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:honeymoon-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0x-f5bdp {
  fill: currentColor;
  d: path("M12 14a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w8a4-ib_b {
  fill: currentColor;
  d: path("M3 9a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xptqu8bzs {
  d: path("M3 9a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.zhn1ajhpt {
  d: path("M12 14a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

</style>
