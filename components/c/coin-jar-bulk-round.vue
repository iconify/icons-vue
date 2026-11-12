<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci_-vopve"/><path class="ldkxcoxeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-bulk-round" /></template>
<style>
.ci_-vopve {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0m7 2a3 3 0 1 1 6 0a3 3 0 0 1-6 0m4 4a1 1 0 0 1 1 1v1.586l.707.707C18.665 15.252 19 16.683 19 18v1a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-1c0-1.317.335-2.748 1.293-3.707L7 13.586V12a1 1 0 0 1 1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ldkxcoxeq {
  d: path("M7 11h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
