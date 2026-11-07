<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ssdm4pbde"/><path class="u7j2zre0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ssdm4pbde {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10h-7a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1");
}

.u7j2zre0r {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m6.042 9.72a6.002 6.002 0 0 1 11.915-1.44a6.001 6.001 0 0 1-11.915 1.44m1.984-1.182a4 4 0 1 0 7.947.923a4 4 0 0 0-7.947-.923M15 17v-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1");
}

</style>
