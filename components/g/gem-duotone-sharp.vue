<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zv_p11bcm"/><path class="qnz-f8bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qnz-f8bjq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5h10l4 4l-9 10L3 9zm1 4l2 2");
}

.zv_p11bcm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 4c.265 0 .52.105.707.293l4 4a1 1 0 0 1 .036 1.376l-9 10a1 1 0 0 1-1.486 0l-9-10a1 1 0 0 1 .036-1.376l4-4A1 1 0 0 1 7 4Z");
}

</style>
