<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tth-uac7z"/><path class="a3chgg7oi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-bulk" /></template>
<style>
.a3chgg7oi {
  d: path("M5 2h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m0 18h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tth-uac7z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a1 1 0 0 1 1 1v3c0 1.039-.578 1.992-1.293 2.707L13.414 12l3.293 3.293C17.422 16.008 18 16.961 18 18v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-3c0-1.039.578-1.992 1.293-2.707L10.586 12L7.293 8.707C6.578 7.992 6 7.039 6 6V3a1 1 0 0 1 1-1");
}

</style>
