<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z5gvel7ot"/><path class="d8ok-v92n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d8ok-v92n {
  d: path("M11.707 9.293L13 10.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M4 9v10a1 1 0 0 0 1 1h10a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V9a1 1 0 0 1 2 0");
}

.z5gvel7ot {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Z");
}

</style>
