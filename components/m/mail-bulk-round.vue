<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kxv0ujoic"/><path class="m__4ylf1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kxv0ujoic {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 20H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20");
}

.m__4ylf1f {
  d: path("m4.424 6.01l3.283 3.283C8.261 9.847 9.248 10 10 10h4c.75 0 1.738-.152 2.293-.707l3.283-3.283a.999.999 0 1 1 1.414 1.414l-3.283 3.283C16.749 11.665 15.316 12 14 12h-4c-1.318 0-2.749-.335-3.707-1.293L3.01 7.424A.999.999 0 1 1 4.424 6.01");
}

</style>
