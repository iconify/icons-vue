<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t-rbnuj5a"/><path class="aevls7bnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-bulk" /></template>
<style>
.aevls7bnl {
  d: path("M8 3h8a3.004 3.004 0 0 1 3 3v3a1 1 0 0 1-2 0V6a1 1 0 0 0-1-1H8l-.05.001h-.001A.984.984 0 0 0 7 6v3a1 1 0 0 1-2 0V5.999A3 3 0 0 1 8 3M7 20a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm12 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.t-rbnuj5a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1h4a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 21 11v5a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
