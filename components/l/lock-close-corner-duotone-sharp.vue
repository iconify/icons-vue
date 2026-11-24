<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v8004ybqc"/><path class="hicj--jca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-close-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hicj--jca {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H4V9h16v2M8 9V7a4 4 0 1 1 8 0v2m0 7l4 4m0-4l-4 4");
}

.v8004ybqc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 21H4V9h7Z");
}

</style>
