<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="crkz45p_z"/><path class="o2to2iddk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fingerprint-bulk-round" /></template>
<style>
.crkz45p_z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 13a5 5 0 0 1 10 0v3a1 1 0 0 1-2 0v-3a3 3 0 1 0-6 0v6a1 1 0 0 1-2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.o2to2iddk {
  d: path("M3 14.06a9.063 9.063 0 0 1 13.496-8.928a1 1 0 1 1-.992 1.736a7.063 7.063 0 0 0-10.512 7.008Q5 13.938 5 14v3a1 1 0 0 1-2 0ZM21 12v4a1 1 0 0 1-2 0v-3.936a7 7 0 0 0-.868-2.568a1 1 0 1 1 1.736-.992a9 9 0 0 1 1.124 3.372Q21 11.938 21 12m-8 6a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0Z");
}

</style>
