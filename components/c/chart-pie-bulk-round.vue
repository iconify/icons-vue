<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vqmzpk28t"/><path class="aope2d4kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-bulk-round" /></template>
<style>
.aope2d4kb {
  d: path("M13 11h8a1 1 0 0 1 0 2h-6.586l4.293 4.293a.999.999 0 1 1-1.414 1.414l-6-6A1 1 0 0 1 11 12V3a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vqmzpk28t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2.049V13h.586l6.743 6.744A10 10 0 0 1 2.26 9.735A10 10 0 0 1 11 2.049M13 11V2.049A10.01 10.01 0 0 1 21.951 11Zm8.951 2a10 10 0 0 1-2.207 5.329L14.414 13Z");
}

</style>
