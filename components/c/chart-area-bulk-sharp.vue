<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hpvg2lb4t"/><path class="mi2ld3b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hpvg2lb4t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 16v-4c0-.265.105-.52.293-.707l3-3a1 1 0 0 1 1.414 0L13 10.586l5.293-5.293A1 1 0 0 1 20 6v10a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

.mi2ld3b2h {
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Z");
}

</style>
