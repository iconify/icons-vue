<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wljdbqb8g"/><path class="u7j2zre0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u7j2zre0r {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m6.042 9.72a6.002 6.002 0 0 1 11.915-1.44a6.001 6.001 0 0 1-11.915 1.44m1.984-1.182a4 4 0 1 0 7.947.923a4 4 0 0 0-7.947-.923M15 17v-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1");
}

.wljdbqb8g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

</style>
