<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ylf3xlbyk"/><path class="kc6uogbct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kc6uogbct {
  d: path("M3 13a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2Z");
}

.ylf3xlbyk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 3a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Zm8 2h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3");
}

</style>
