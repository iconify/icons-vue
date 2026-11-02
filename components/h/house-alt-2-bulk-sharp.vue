<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hmioahcew"/><path class="gt71-xrst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gt71-xrst {
  d: path("M3 21a1 1 0 0 1 0-2h6v-3a3 3 0 1 1 6 0v3h6a1 1 0 0 1 0 2Zm10-2v-3a1 1 0 0 0-2 0v3Z");
}

.hmioahcew {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 11c0-.265.105-.52.293-.707l7-7a1 1 0 0 1 1.414 0l7 7A1 1 0 0 1 20 11v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm10 5a2 2 0 1 0-4 0v4h4Z");
}

</style>
