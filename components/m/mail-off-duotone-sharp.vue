<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kg0x_qbrl"/><path class="emo1oviix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-duotone-sharp" /></template>
<style>
.emo1oviix {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H3V5h2m6 0h10v10m-2 4h-7m4-9l5-5M2 2l20 20");
}

.ft5dv1b6b {
  fill: none;
}

.kg0x_qbrl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 19H3V5h2ZM11 5h10v10Z");
}

</style>
