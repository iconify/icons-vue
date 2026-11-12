<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jo5lz5bcg"/><path class="v800_2rhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jo5lz5bcg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.707 5.293l6 6a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 14 17h-2.586l-4.707 4.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 0-1.414L7 12.586V10c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0");
}

.v800_2rhu {
  d: path("m9.707 8.293l6 6a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414");
}

</style>
