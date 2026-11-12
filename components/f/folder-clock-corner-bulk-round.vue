<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wvphlzbwh"/><path class="ux62gzu1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-clock-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ux62gzu1d {
  d: path("M11 16.998a6 6 0 1 1 12-.004a6 6 0 0 1-12 .008V17ZM13 17a4 4 0 1 0 8 0a4 4 0 0 0-8 0m3-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1Z");
}

.wvphlzbwh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

</style>
