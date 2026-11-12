<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci4d-ib1s"/><path class="cspqc4c2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pause-corner-bulk" /></template>
<style>
.ci4d-ib1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.cspqc4c2z {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm2 14a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
