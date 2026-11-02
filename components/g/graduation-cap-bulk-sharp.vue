<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pohwrqbjx"/><path class="djug5xpex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.djug5xpex {
  d: path("M21 15a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0ZM8.447 11.106L12 12.882l3.553-1.776a1 1 0 1 1 .894 1.788l-4 2a1 1 0 0 1-.894 0l-4-2a1 1 0 1 1 .894-1.788");
}

.pohwrqbjx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.447 5.106l8 4a.998.998 0 0 1 0 1.788L17 12.618V16c0 .53-.211 1.023-.551 1.424c-1.78 2.103-7.118 2.103-8.898 0C7.211 17.023 7 16.53 7 16v-3.382l-3.447-1.724a.998.998 0 0 1 0-1.788l8-4a1 1 0 0 1 .894 0");
}

</style>
