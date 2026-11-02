<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="md1d0fb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-treemap-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.md1d0fb5h {
  d: path("M11 9h10a1 1 0 0 1 0 2h-4v10a1 1 0 0 1-2 0V11h-4v10a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Z");
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
