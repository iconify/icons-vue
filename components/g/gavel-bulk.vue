<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ecd_ouslz"/><path class="z9bm6466g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gavel-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ecd_ouslz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.707 20.707a3.121 3.121 0 1 1-4.414-4.414L10.586 9l-.293-.293a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0l5 5a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0L15 13.414Z");
}

.z9bm6466g {
  d: path("m13.396 11.81l-1.206-1.206a.999.999 0 1 1 1.414-1.414l1.206 1.206a.999.999 0 1 1-1.414 1.414M13 21a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2Z");
}

</style>
