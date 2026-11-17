<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mcj8-1bcc"/><path class="pj220gbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mcj8-1bcc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.872 21.872A3 3 0 0 1 18 22H6a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3Zm2.051-2.192L10.243 9H18a3 3 0 0 1 3 3v7q0 .345-.077.68");
}

.pj220gbcd {
  d: path("M16 6v4a1 1 0 0 1-2 0V6a2 2 0 1 0-4 0a1 1 0 0 1-2 0a4 4 0 0 1 8 0M2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
