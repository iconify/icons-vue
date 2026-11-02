<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q1ndt2nsh"/><path class="iuikh0ban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-check-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iuikh0ban {
  d: path("m11 12.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

.q1ndt2nsh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9v6c0 1.693-1.069 3.152-2.553 3.894l-4 2a5.47 5.47 0 0 1-4.894 0l-4-2C4.069 18.152 3 16.693 3 15V9c0-1.693 1.069-3.152 2.553-3.894l4-2a5.47 5.47 0 0 1 4.894 0l4 2C19.931 5.848 21 7.307 21 9");
}

</style>
