<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wljdbqb8g"/><path class="ra732ow-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sync-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ra732ow-q {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m14 8a1 1 0 0 1 0-2h.748a5 5 0 0 0-.195-.106l-.003-.001a3.473 3.473 0 0 0-4.656 1.554a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.47 5.47 0 0 1 6.316-1.025l.005.002q.284.142.548.315V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.548.892h-.002l-.001.002h-.001A1 1 0 0 1 21 16Zm-4 5.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .963-.999h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894A5.465 5.465 0 0 1 14 21.577");
}

.wljdbqb8g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

</style>
