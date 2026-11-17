<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cmy1aeb-f"/><path class="ohs7azhmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fence-bulk-round" /></template>
<style>
.cmy1aeb-f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7c0-.155.036-.308.106-.447l1.552-3.106a1.5 1.5 0 0 1 2.684 0l1.552 3.106c.07.139.106.292.106.447v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm10 0c0-.155.036-.308.106-.447l1.552-3.106a1.5 1.5 0 0 1 2.684 0l1.552 3.106c.07.139.106.292.106.447v14a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ohs7azhmj {
  d: path("M3 9h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6 0h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m10 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2M3 15h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6 0h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m10 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

</style>
