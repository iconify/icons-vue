<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fme_di6cc"/><path class="s7f6evnmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fme_di6cc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 5a1 1 0 0 1 1 1v8a1 1 0 0 1-2 0V7h-7a1 1 0 0 1 0-2Z");
}

.s7f6evnmh {
  d: path("M7 6v11h14a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H6a1 1 0 0 1-1-1V7H3a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0Z");
}

</style>
