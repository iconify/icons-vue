<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mo0d_wboa"/><path class="t-qzdgb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:download-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mo0d_wboa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19h14v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0Z");
}

.t-qzdgb7e {
  d: path("m11.293 16.707l-4-4a.999.999 0 1 1 1.414-1.414L11 13.586V4a1 1 0 0 1 2 0v9.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
