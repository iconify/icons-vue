<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rb8whx5-l"/><path class="w_mgzj-rr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rb8whx5-l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3h12v14H7V6Z");
}

.w_mgzj-rr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h12v14H7V6zm12 4h4v6h-4M6 21h12");
}

</style>
