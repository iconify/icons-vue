<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t473xod8i"/><path class="suos79b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.suos79b9h {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2ZM8 13h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m-8 4h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

.t473xod8i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
