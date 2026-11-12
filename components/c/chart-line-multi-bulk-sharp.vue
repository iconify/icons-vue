<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="auot9qa9q"/><path class="t-r8uvbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-multi-bulk-sharp" /></template>
<style>
.auot9qa9q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.4 12.2a1 1 0 0 1 1.047-.094l3.415 1.707l5.498-4.581a1 1 0 1 1 1.28 1.536l-6 5a1 1 0 0 1-1.087.126l-3.447-1.723L7.6 16.8a1.002 1.002 0 0 1-1.593-.68a1 1 0 0 1 .393-.92Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.t-r8uvbit {
  d: path("m6.293 9.293l4-4A1 1 0 0 1 11.6 5.2l3.306 2.48l5.387-5.387a.999.999 0 1 1 1.414 1.414l-6 6A1 1 0 0 1 14.4 9.8l-3.306-2.48l-3.387 3.387a.999.999 0 1 1-1.414-1.414M4 4v15h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0");
}

</style>
