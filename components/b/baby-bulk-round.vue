<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="qp2gnmpjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:baby-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qp2gnmpjj {
  d: path("M12 4a1 1 0 0 0-.922 1.387A.99.99 0 0 0 12 6a1 1 0 0 1 0 2a3 3 0 0 1 0-6a1 1 0 0 1 0 2M9 9h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6.293 5.293a4.66 4.66 0 0 0 6.586 0a1 1 0 1 1 1.414 1.414a6.656 6.656 0 0 1-9.414 0a.999.999 0 1 1 1.414-1.414");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
