<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s_j962yua"/><path class="gv9ej_bxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ferris-wheel-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gv9ej_bxu {
  d: path("M4.211 8.162c.199-.837.53-1.637.982-2.369a2.002 2.002 0 0 1 2.6-2.6a8.03 8.03 0 0 1 8.414 0a2.002 2.002 0 0 1 2.6 2.6c.452.732.783 1.532.982 2.369a2.001 2.001 0 0 1 0 3.676a8 8 0 0 1-3.441 4.88L18.535 20H20a1.002 1.002 0 0 1 .866 1.5A1 1 0 0 1 20 22H4a1 1 0 1 1 0-2h1.465l2.188-3.282a8.04 8.04 0 0 1-3.442-4.88a2 2 0 0 1 0-3.676M14.829 9h2.438c.133-.229.31-.43.521-.591a6 6 0 0 0-.571-1.376a2.002 2.002 0 0 1-2.25-2.25a6.01 6.01 0 0 0-5.934 0a2.002 2.002 0 0 1-2.25 2.25a6 6 0 0 0-.57 1.376c.21.161.387.362.52.591h2.438a3 3 0 0 1 5.658 0M13 10v-.01a1 1 0 1 0 0 .02Zm-6.267 1a2 2 0 0 1-.52.591a6.02 6.02 0 0 0 2.549 3.463l1.666-2.498A3 3 0 0 1 9.171 11Zm8.505 4.054a6.04 6.04 0 0 0 2.55-3.463a2 2 0 0 1-.521-.591h-2.438a3 3 0 0 1-1.256 1.556Zm-1.876.792L12 13.803l-1.362 2.043a6.1 6.1 0 0 0 2.724 0M7.869 20h8.262l-1.604-2.407a8.04 8.04 0 0 1-5.054 0Z");
}

.s_j962yua {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.236 8.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
