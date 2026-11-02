<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zz3jffbbq"/><path class="hywcwmb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hywcwmb5h {
  d: path("M9.01 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm1.697 6.707a.999.999 0 1 1-1.414-1.414l4-4a.999.999 0 1 1 1.414 1.414ZM15 14h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2");
}

.zz3jffbbq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 19H6a4 4 0 0 1-4-4a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1a4 4 0 0 1 4-4h12a4 4 0 0 1 4 4a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1a4 4 0 0 1-4 4");
}

</style>
