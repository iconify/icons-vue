<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ztvb5gbuj"/><path class="i-wxpsbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i-wxpsbzo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9.75 9.75 0 0 1 18 0a9.75 9.75 0 0 1-18 0m7 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ztvb5gbuj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 12a9.75 9.75 0 0 1-18 0a9.75 9.75 0 0 1 18 0m-9 2a2 2 0 1 0 .001-3.999A2 2 0 0 0 12 14");
}

</style>
