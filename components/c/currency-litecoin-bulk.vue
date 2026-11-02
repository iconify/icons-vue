<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_4_sbc_s"/><path class="hwnq-ct1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-litecoin-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hwnq-ct1o {
  d: path("M10 18h9a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1V5a1 1 0 0 1 2 0Z");
}

.m_4_sbc_s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.553 10.106a1 1 0 1 1 .894 1.788l-8 4a1 1 0 1 1-.894-1.788Z");
}

</style>
