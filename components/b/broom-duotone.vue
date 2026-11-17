<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zo40_qonv"/><path class="gt2a6aclq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gt2a6aclq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H4l4-8h8l4 8zm-2 0v-3m4 3v-3M12 3v9");
}

.zo40_qonv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 12h8l4 8H4Z");
}

</style>
