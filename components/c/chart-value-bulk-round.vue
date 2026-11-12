<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="d4d_b1bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-value-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d4d_b1bjs {
  d: path("M7.293 8.293A1 1 0 0 1 9 9v6a1 1 0 0 1-2 0v-3.586l-.293.293a.999.999 0 1 1-1.414-1.414ZM19 9v4a1 1 0 0 1-2 0v-1.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L15.586 10H14a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1");
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

</style>
