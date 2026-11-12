<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zhtyywbhi"/><path class="w1yyuzw7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hdmi-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w1yyuzw7k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h7a2 2 0 0 1 2 2v2l-4 6H7l-4-6V9a2 2 0 0 1 2-2zm-4 4h8");
}

.zhtyywbhi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 6a3 3 0 0 1 3 3v2a1 1 0 0 1-.168.555l-4 6A1 1 0 0 1 17 18H7a1 1 0 0 1-.832-.445l-4-6A1 1 0 0 1 2 11V9a3 3 0 0 1 3-3Z");
}

</style>
