<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="puqfzcbzs"/><path class="ac78zwt4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-bulk-sharp" /></template>
<style>
.ac78zwt4g {
  d: path("M9 3h4a1 1 0 0 1 0 2h-1v3a1 1 0 0 1-2 0V5H9a1 1 0 0 1 0-2M2 15v-4a1 1 0 0 1 2 0v1h2a1 1 0 0 1 0 2H4v1a1 1 0 0 1-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.puqfzcbzs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7h4c.379 0 .725.214.894.553L15.618 11H17v-1a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-1h-2v3a1 1 0 0 1-1 1h-4a1 1 0 0 1-.894-.553L7.382 17H6a1 1 0 0 1-1-1v-5c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 9 7");
}

</style>
