<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hjfyr2buj"/><path class="vym_e1rkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-4-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hjfyr2buj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.322 4.615l6.342 5.638a1 1 0 0 1 .334.688a1 1 0 0 1-.251.723l-.013.015a1 1 0 0 1-1.412.083L20 11.476V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-5.524l-.322.286a1 1 0 0 1-1.412-.083l-.013-.015a1 1 0 0 1 .083-1.411l6.342-5.638a5 5 0 0 1 6.644 0");
}

.vym_e1rkj {
  d: path("M11 18a3 3 0 0 1-3-3v-2.435c0-.857.366-1.673 1.007-2.242l1-.889a3 3 0 0 1 3.986 0l1 .889A3 3 0 0 1 16 12.565V15a3 3 0 0 1-3 3Zm2-2a.997.997 0 0 0 1-1v-2.435a1 1 0 0 0-.336-.748l-1-.888a1 1 0 0 0-1.328-.001l-1 .889a1 1 0 0 0-.336.748V15a.997.997 0 0 0 1 1Z");
}

</style>
