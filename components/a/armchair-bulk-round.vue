<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gd36r_bqy"/><path class="o4g0hhb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gd36r_bqy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1h4a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 21 11v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 19H8a5 5 0 0 1-5-5Z");
}

.o4g0hhb1r {
  d: path("M5 8a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v1a1 1 0 0 1-2 0V8a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v1a1 1 0 0 1-2 0Zm2 12a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm12 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
