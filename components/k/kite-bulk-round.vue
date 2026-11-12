<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="khpg91b6z"/><path class="ulbaxpbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.khpg91b6z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m20.707 10.707l-7 7a2.414 2.414 0 0 1-3.414 0l-7-7c-.2-.2-.335-.451-.396-.727c-.324-1.472 1.468-3.092 2.548-3.812l6-4a1 1 0 0 1 1.11 0l6 4c1.08.72 2.872 2.34 2.548 3.812a1.47 1.47 0 0 1-.396.727");
}

.ulbaxpbrv {
  d: path("M13 7v1h6.956a1 1 0 0 1 0 2H13v8c0 .189.033.38.117.55c.08.164.202.303.34.42c.427.36 1.002.551 1.536.685C16.29 19.979 17.669 20 19 20a1 1 0 0 1 0 2c-2.399 0-6.463-.087-7.679-2.57A3.25 3.25 0 0 1 11 18v-8H4.044a1 1 0 0 1 0-2H11V3a1 1 0 0 1 2 0Z");
}

</style>
