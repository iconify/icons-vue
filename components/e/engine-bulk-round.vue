<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="teu09jw3s"/><path class="ac78zwt4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-bulk-round" /></template>
<style>
.ac78zwt4g {
  d: path("M9 3h4a1 1 0 0 1 0 2h-1v3a1 1 0 0 1-2 0V5H9a1 1 0 0 1 0-2M2 15v-4a1 1 0 0 1 2 0v1h2a1 1 0 0 1 0 2H4v1a1 1 0 0 1-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.teu09jw3s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 11v6a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2h-2v2a2 2 0 0 1-2 2h-3a1 1 0 0 1-.894-.553L7.382 17H7a2 2 0 0 1-2-2v-4c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 9 7h4c.379 0 .725.214.894.553L15.618 11H17a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2");
}

</style>
