<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zv0ky1bfi"/><path class="x3y6ph7ke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-check-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x3y6ph7ke {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m12.933 10.519l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

.zv0ky1bfi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7v2H10v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3");
}

</style>
