<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q3rkgq6ia"/><path class="b1jnfbfts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-unordered-bulk" /></template>
<style>
.b1jnfbfts {
  d: path("M19 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.q3rkgq6ia {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.01 6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
