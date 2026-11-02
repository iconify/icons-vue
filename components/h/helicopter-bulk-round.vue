<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gb8tydpvb"/><path class="zokdmejfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gb8tydpvb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 11c0-1.33.522-2.597 1.464-3.536A4.98 4.98 0 0 1 13 6c2.213 0 4.473.62 6.258 1.959c.799.6 1.492 1.343 1.985 2.216c.486.863.757 1.832.757 2.825a4.995 4.995 0 0 1-5 5h-6a3 3 0 0 1-3-3Z");
}

.zokdmejfu {
  d: path("M5 2h16a1 1 0 0 1 0 2h-7v7a1 1 0 0 0 1 1h6a1 1 0 0 1 0 2h-6a3 3 0 0 1-3-3V4H5a1 1 0 0 1 0-2M4 16a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0v2h5a1 1 0 0 1 0 2H4Zm5 4h3v-3a1 1 0 0 1 2 0v3h2v-3a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
