<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z0xrbflmn"/><path class="u7-5ntbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cog-railway-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u7-5ntbax {
  d: path("M19.553 11.106a1 1 0 1 1 .894 1.788l-1.105.553l.552 1.106a1 1 0 0 1-.954 1.445a1 1 0 0 1-.834-.551l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-1.106.552a1 1 0 0 1-1.445-.954a1 1 0 0 1 .551-.834Z");
}

.z0xrbflmn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19V7a1 1 0 0 1 1-1h4V4a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v9a1 1 0 0 1-.553.894l-12 6A1 1 0 0 1 5 19m7-11h5V5h-5Zm-2 3V8H7v3Z");
}

</style>
