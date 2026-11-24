<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v8xhjm3ii"/><path class="t8jh3siyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.t8jh3siyy {
  d: path("M15.5 12a1 1 0 0 1 2 0v.5a1 1 0 0 1-2 0Zm-2.889 2.025a.999.999 0 1 1 1.414-1.414l.354.353c.39.391.39 1.024 0 1.415c-.391.39-1.024.39-1.415 0Zm6.364-1.414a.999.999 0 1 1 1.414 1.414l-.353.354a1 1 0 0 1-1.415-1.415Zm-4.317 3.11a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M12 17.5a1 1 0 0 1 0-2h.5a1 1 0 0 1 0 2Zm9-2a1 1 0 0 1 0 2h-.5a1 1 0 0 1 0-2Zm-6.975 4.889a.999.999 0 1 1-1.414-1.414l.353-.354a1 1 0 0 1 1.415 1.415Zm6.364-1.414a.999.999 0 1 1-1.414 1.414l-.354-.353a1 1 0 0 1 0-1.415a1 1 0 0 1 1.415 0ZM17.5 21a1 1 0 0 1-2 0v-.5a1 1 0 0 1 2 0Z");
}

.v8xhjm3ii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9");
}

</style>
