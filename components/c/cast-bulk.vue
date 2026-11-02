<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d5k72gaca"/><path class="u9ukn6b4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cast-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d5k72gaca {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5h7a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

.u9ukn6b4k {
  d: path("M5 4h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-4a1 1 0 0 1 0-2h4a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3m-2 6a9 9 0 0 1 9 9a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.55-2.724a6.9 6.9 0 0 0-1.5-2.226A6.97 6.97 0 0 0 3 12a1 1 0 0 1 0-2m0 4c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 8 19a1 1 0 0 1-2 0a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 3 16a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
