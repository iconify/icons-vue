<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qm7hk4bcg"/><path class="hoqij-ggl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hoqij-ggl {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.388-1.388A3.04 3.04 0 0 1 18 22H6a3.004 3.004 0 0 1-3-3V7c0-.69.246-1.37.681-1.905L1.293 2.707a.999.999 0 1 1 1.414-1.414M15 3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v7a1 1 0 0 1-2 0V7a1 1 0 0 0-1-1h-7a1 1 0 0 1 0-2h4ZM5 7v12a1 1 0 0 0 1 1h12a1 1 0 0 0 .469-.116L5.116 6.531A1 1 0 0 0 5 7");
}

.qm7hk4bcg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.291 5.705A1 1 0 0 1 11 4h7a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1h-5.414ZM4.438 4.438L10 10H4a1 1 0 0 1-1-1V7c0-1.047.544-2.018 1.438-2.562");
}

</style>
