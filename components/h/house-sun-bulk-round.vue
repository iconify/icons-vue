<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3cwdvb-i"/><path class="mu_csexni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mu_csexni {
  d: path("M11 8.5a1 1 0 0 1 2 0V9a1 1 0 0 1-2 0Zm-2.889 2.025a.999.999 0 1 1 1.414-1.414l.354.353c.39.391.39 1.024 0 1.415c-.391.39-1.024.39-1.415 0Zm6.364-1.414a.999.999 0 1 1 1.414 1.414l-.353.354c-.391.39-1.024.39-1.415 0a1 1 0 0 1 0-1.415Zm-4.317 3.11a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M7.5 14a1 1 0 0 1 0-2H8a1 1 0 0 1 0 2Zm9-2a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-6.975 4.889a.999.999 0 1 1-1.414-1.414l.353-.354a1 1 0 0 1 1.415 0c.39.391.39 1.024 0 1.415Zm6.364-1.414a.999.999 0 1 1-1.414 1.414l-.354-.353a1 1 0 0 1 0-1.415a1 1 0 0 1 1.415 0ZM13 17.5a1 1 0 0 1-2 0V17a1 1 0 0 1 2 0Z");
}

.o3cwdvb-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

</style>
