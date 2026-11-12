<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ine9413lu"/><path class="ldkxcoxeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ine9413lu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0m7 2a3 3 0 1 1 6 0a3 3 0 0 1-6 0m4 4a1 1 0 0 1 1 1v1.586l.707.707C18.422 15.008 19 15.961 19 17v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2c0-1.039.578-1.992 1.293-2.707L7 13.586V12a1 1 0 0 1 1-1Z");
}

.ldkxcoxeq {
  d: path("M7 11h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
