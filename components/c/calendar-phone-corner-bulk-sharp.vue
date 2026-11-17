<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wljdbqb8g"/><path class="x3-stebto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-phone-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wljdbqb8g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 4h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

.x3-stebto {
  d: path("M7 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm8 0a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m8 5.889V13a1 1 0 0 1 1-1h2.667a1 1 0 0 1 .928.629l.889 2.222a1 1 0 0 1-.221 1.078l-.627.627l.808.808l.627-.627a1 1 0 0 1 1.078-.221l2.222.889a1 1 0 0 1 .629.928V21a1 1 0 0 1-1 1h-.889A8.11 8.11 0 0 1 12 13.889");
}

</style>
