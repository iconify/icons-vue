<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qab80b9mo"/><path class="j31xqfa0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-help-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j31xqfa0v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l8 7v11H4V10zm-2 10a2 2 0 1 1 2 2m0 3h.01");
}

.qab80b9mo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 10v11H4V10l8-7Z");
}

</style>
