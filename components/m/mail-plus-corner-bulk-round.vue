<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dbozn_bdh"/><path class="v36f3acps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dbozn_bdh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-6c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v4a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v2a1 1 0 0 1-1 1");
}

.v36f3acps {
  d: path("m4.424 6.01l3.283 3.283C8.261 9.847 9.248 10 10 10h4c.749 0 1.737-.152 2.293-.707l3.283-3.283a.999.999 0 1 1 1.414 1.414l-3.107 3.107l-.001.001l-.175.175C16.748 11.665 15.317 12 14 12h-4c-1.318 0-2.749-.335-3.707-1.293L3.01 7.424A.999.999 0 1 1 4.424 6.01M19 17h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

</style>
