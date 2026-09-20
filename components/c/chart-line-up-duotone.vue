<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="onrdkub8r"/><path class="vr94xfo8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-line-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.onrdkub8r {
  d: path("M224 64v144H32V48h176a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vr94xfo8d {
  d: path("M232 208a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V48a8 8 0 0 1 16 0v108.69l50.34-50.35a8 8 0 0 1 11.32 0L128 132.69L180.69 80H160a8 8 0 0 1 0-16h40a8 8 0 0 1 8 8v40a8 8 0 0 1-16 0V91.31l-58.34 58.35a8 8 0 0 1-11.32 0L96 123.31l-56 56V200h184a8 8 0 0 1 8 8");
}

</style>
