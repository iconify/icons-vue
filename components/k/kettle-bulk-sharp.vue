<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n7jqkyb7o"/><path class="zn6xkq-9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n7jqkyb7o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 2a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V6.414L3.293 3.707A1 1 0 0 1 4 2Z");
}

.zn6xkq-9r {
  d: path("M16 6h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3V8h-3a1 1 0 0 1 0-2M6 20h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
