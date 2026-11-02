<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d68-isbpo"/><path class="i2owb1n5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d68-isbpo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2h4a1 1 0 0 1 1 1v5.764l5.894 11.789A1 1 0 0 1 20 22H4a1 1 0 0 1-.894-1.447L9 8.764V3a1 1 0 0 1 1-1");
}

.i2owb1n5a {
  d: path("M8 4a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2ZM7 14h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
