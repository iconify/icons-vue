<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k1jpp7b_t"/><path class="uez0o3g6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k1jpp7b_t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.707 8.293l2 2a2.414 2.414 0 0 1 0 3.414l-3 3A1 1 0 0 1 14 17h-2.586l-3.707 3.707a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414L7 12.586V10c0-.265.105-.52.293-.707l3-3a2.414 2.414 0 0 1 3.414 0Z");
}

.uez0o3g6x {
  d: path("M20.293 2.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414-1.414ZM17 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-5.293 7.293a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
