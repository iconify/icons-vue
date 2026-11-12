<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mda-2_b-w"/><path class="vypjh52qh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mda-2_b-w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5v12a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

.vypjh52qh {
  d: path("M21 9a1 1 0 0 1-2 0V6.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L17.586 5H15a1 1 0 0 1 0-2h5a.997.997 0 0 1 1 1ZM10 6H7a.997.997 0 0 0-1 1v10a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1v-3a1 1 0 0 1 2 0v3a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h3a1 1 0 0 1 0 2");
}

</style>
