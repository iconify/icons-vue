<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y7hl_mbmd"/><path class="bj_g0ob5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-bulk-sharp" /></template>
<style>
.bj_g0ob5a {
  d: path("M19 10h-6a1 1 0 0 1-1-1V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-2h2.586L14 5.414Zm-5.764 3.832A3 3 0 1 1 11 16a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 10 13a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M11.01 17a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.y7hl_mbmd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Z");
}

</style>
