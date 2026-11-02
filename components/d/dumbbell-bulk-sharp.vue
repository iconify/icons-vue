<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jm-ad3b0o"/><path class="sc-ep82on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jm-ad3b0o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 4h4a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-2H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h1V5a1 1 0 0 1 1-1m10 0h4a1 1 0 0 1 1 1v2h1a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-1v2a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

.sc-ep82on {
  d: path("M9 13a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2Z");
}

</style>
