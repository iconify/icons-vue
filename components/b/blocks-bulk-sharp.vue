<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u6t72abda"/><path class="y8hxjtb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blocks-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u6t72abda {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1ZM9 5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1ZM2 21v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m17 0a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1Z");
}

.y8hxjtb_m {
  d: path("M14 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Z");
}

</style>
