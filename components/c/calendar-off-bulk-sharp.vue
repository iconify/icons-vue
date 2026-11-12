<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ofa6nabhw"/><path class="jbb6cgk7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jbb6cgk7b {
  d: path("m9.707 8.293l13 13a.999.999 0 1 1-1.414 1.414L8.586 10H4a1 1 0 0 1 0-2h2.586L1.293 2.707a.999.999 0 1 1 1.414-1.414ZM17 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2Z");
}

.ofa6nabhw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4 4l17 17a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m17 12.757L8.243 4H20a1 1 0 0 1 1 1Z");
}

</style>
