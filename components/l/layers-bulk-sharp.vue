<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ba9qrbb8a"/><path class="vs-8b8bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layers-bulk-sharp" /></template>
<style>
.ba9qrbb8a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.553 5.106l4-2a1 1 0 0 1 .894 0l8 4a.998.998 0 0 1 0 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a.998.998 0 0 1 0-1.788Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vs-8b8bpm {
  d: path("M4.447 11.106L12 14.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788m0 4L12 18.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788");
}

</style>
