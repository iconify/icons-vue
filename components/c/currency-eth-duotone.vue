<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="araa3kb4w"/><path class="banuk0v-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-eth-duotone" /></template>
<style>
.araa3kb4w {
  d: path("m216 128l-88 112l-88-112l88 40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.banuk0v-f {
  d: path("m222.29 123.06l-88-112a8 8 0 0 0-12.58 0l-88 112a8 8 0 0 0 0 9.88l88 112a8 8 0 0 0 12.58 0l88-112a8 8 0 0 0 0-9.88M136 39.13l67.42 85.8L136 155.58Zm-16 116.45l-67.42-30.65L120 39.13Zm0 17.57v43.72l-53.43-68Zm16 0l53.43-24.29l-53.43 68Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
