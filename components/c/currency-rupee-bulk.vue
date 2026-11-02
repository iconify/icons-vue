<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epei0bcwt"/><path class="cprgajb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-rupee-bulk" /></template>
<style>
.cprgajb8g {
  d: path("M18 4a1 1 0 0 1 0 2h-3.999A5.002 5.002 0 0 1 10 14H8.414l4.293 4.293a.999.999 0 1 1-1.414 1.414l-6-6A1 1 0 0 1 6 12h4a3 3 0 1 0 0-6H6a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.epei0bcwt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 8h4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
