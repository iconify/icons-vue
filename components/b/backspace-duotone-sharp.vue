<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i--tnib-u"/><path class="yhlkr8hke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i--tnib-u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 12l6-6h12v12H9Z");
}

.yhlkr8hke {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 12l6-6h12v12H9zm10-2l4 4m0-4l-4 4");
}

</style>
