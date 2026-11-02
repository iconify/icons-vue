<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hk-ncvb_z"/><path class="qulk_jbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-sparkle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hk-ncvb_z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 21a9 9 0 0 1-9-9a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9m5-9c-2.998-.002-4.998-2.002-5-5c-.002 2.998-2.002 4.998-5 5c2.998.002 4.998 2.002 5 5c.002-2.998 2.002-4.998 5-5");
}

.qulk_jbzc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m9-5c0 3 2 5 5 5c-3 0-5 2-5 5c0-3-2-5-5-5c3 0 5-2 5-5");
}

</style>
