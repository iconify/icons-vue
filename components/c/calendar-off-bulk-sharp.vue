<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mc9wz2s3o"/><path class="u19cffl1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mc9wz2s3o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4 4l6 6H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m9.586 5l-3.295-3.295A1 1 0 0 1 11 4h9a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5.414Z");
}

.u19cffl1l {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L20.586 22H4a1 1 0 0 1-1-1V4.414L1.293 2.707a.999.999 0 1 1 1.414-1.414M15 3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v9a1 1 0 0 1-2 0V6h-8a1 1 0 0 1 0-2h4ZM5 20h13.586L5 6.414Z");
}

</style>
