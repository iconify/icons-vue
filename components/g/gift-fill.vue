<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="xdipcdxgp"/><path class="nd4g7tlbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gift-fill" /></template>
<style>
.nd4g7tlbc {
  d: path("M12 7C9 7 7 6 7 4.5C7 3.11929 8.11929 2 9.5 2C11.5 2 12 5 12 7ZM12 7C15 7 17 6 17 4.5C17 3.11929 15.8807 2 14.5 2C12.5 2 12 5 12 7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xdipcdxgp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 8C1 6.895431 1.895431 6 3 6L21 6C22.104569 6 23 6.895431 23 8L23 10C23 11.104569 22.104569 12 21 12L21 12L21 19C21 21.209139 19.209139 23 17 23L7 23C4.790861 23 3 21.209139 3 19L3 12L3 12C1.895431 12 1 11.104569 1 10ZM3 8H21V10H3Z");
  stroke: none;
}

</style>
