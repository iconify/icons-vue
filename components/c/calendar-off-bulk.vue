<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uaq84bhml"/><path class="jbb6cgk7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jbb6cgk7b {
  d: path("m9.707 8.293l13 13a.999.999 0 1 1-1.414 1.414L8.586 10H4a1 1 0 0 1 0-2h2.586L1.293 2.707a.999.999 0 1 1 1.414-1.414ZM17 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2Z");
}

.uaq84bhml {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 16.757L8.243 4H18a3 3 0 0 1 3 3ZM4.438 4.438l16.124 16.124A3 3 0 0 1 18 22H6a3 3 0 0 1-3-3V7c0-1.047.544-2.018 1.438-2.562");
}

</style>
