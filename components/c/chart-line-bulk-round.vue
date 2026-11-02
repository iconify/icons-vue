<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci1x_rbrb"/><path class="dg93bsbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-bulk-round" /></template>
<style>
.ci1x_rbrb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16a3 3 0 0 0 3 3h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dg93bsbaj {
  d: path("M5.293 12.293a3.826 3.826 0 0 1 5.414 0a1.83 1.83 0 0 0 2.586 0l7-7a.999.999 0 1 1 1.414 1.414l-7 7a3.826 3.826 0 0 1-5.414 0a1.83 1.83 0 0 0-2.586 0l-3 3a.999.999 0 1 1-1.414-1.414Z");
}

</style>
