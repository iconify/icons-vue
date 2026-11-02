<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a5hsv5frm"/><path class="lpz8hlb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gallery-bulk" /></template>
<style>
.a5hsv5frm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lpz8hlb9a {
  d: path("M7.293 7.293a2.415 2.415 0 0 1 3.414 0l3 3a.415.415 0 0 0 .586 0l1-1a2.415 2.415 0 0 1 3.414 0l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.415.415 0 0 0-.586 0l-1 1a2.415 2.415 0 0 1-3.414 0l-3-3a.415.415 0 0 0-.586 0l-5 5a.999.999 0 1 1-1.414-1.414ZM10 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm11 0a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2Z");
}

</style>
