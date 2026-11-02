<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lf8acxbvk"/><path class="adg7etx2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-duotone-sharp" /></template>
<style>
.adg7etx2n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h6v12H9ZM4 3v18M20 3v18");
}

.ft5dv1b6b {
  fill: none;
}

.lf8acxbvk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6h6v12H9Z");
}

</style>
