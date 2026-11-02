<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qy1qzbe5h"/><path class="oidse6wjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-help-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oidse6wjy {
  d: path("M9 11a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 11a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.qy1qzbe5h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 7v10a1 1 0 0 1-.553.894l-8 4a1 1 0 0 1-.894 0l-8-4A1 1 0 0 1 3 17V7c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 7");
}

</style>
