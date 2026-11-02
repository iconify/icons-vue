<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z6wzqpb1u"/><path class="k4smnu93g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:facebook-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k4smnu93g {
  d: path("M7 9h11a.998.998 0 0 1 .97 1.243l-1 4A1 1 0 0 1 17 15H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1");
}

.z6wzqpb1u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 10a1 1 0 0 1 1-1h2V8a6 6 0 0 1 6-6h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-3v1h3a.998.998 0 0 1 .97 1.243l-1 4A1 1 0 0 1 17 15h-2v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6H7a1 1 0 0 1-1-1Z");
}

</style>
