<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nhv1wxbdo"/><path class="u-2brwj7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nhv1wxbdo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 14h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

.u-2brwj7e {
  d: path("M14 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-4 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
