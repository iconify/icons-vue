<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gsmo02b9v"/><path class="d38ys1g8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-duotone-sharp" /></template>
<style>
.d38ys1g8f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 16l7-12l7 12Zm0 4h14");
}

.ft5dv1b6b {
  fill: none;
}

.gsmo02b9v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m5 16l7-12l7 12Z");
}

</style>
