<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a40cnohgw"/><path class="oy-jc9bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-bulk-sharp" /></template>
<style>
.a40cnohgw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.555 2.168l9 6a.998.998 0 0 1 .152 1.539l-9 9a1 1 0 0 1-1.414 0l-9-9a.998.998 0 0 1 .152-1.539l9-6a1 1 0 0 1 1.11 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oy-jc9bbh {
  d: path("M13 7v1h8a1 1 0 0 1 0 2h-8v8c0 .189.033.38.117.55c.08.164.202.303.34.42c.427.36 1.002.551 1.536.685C16.29 19.979 17.669 20 19 20a1 1 0 0 1 0 2c-2.399 0-6.463-.087-7.679-2.57A3.25 3.25 0 0 1 11 18v-8H3a1 1 0 0 1 0-2h8V3a1 1 0 0 1 2 0Z");
}

</style>
