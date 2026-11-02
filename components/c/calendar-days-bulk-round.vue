<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rovwibb1o"/><path class="suos79b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rovwibb1o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 9a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

.suos79b9h {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM8 13h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m-8 4h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
