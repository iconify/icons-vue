<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gj2_4-blh"/><path class="ah77tub-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:glass-water-bulk-round" /></template>
<style>
.ah77tub-x {
  d: path("M6 11h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gj2_4-blh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m18.994 12.11l-.605 5.442A5 5 0 0 1 13.42 22h-2.84a5 5 0 0 1-4.969-4.448L4.448 7.086A4.577 4.577 0 0 1 9 2h6a4.58 4.58 0 0 1 4.552 5.086Z");
}

</style>
