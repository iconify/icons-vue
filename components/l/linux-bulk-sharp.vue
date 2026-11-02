<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g75xvebbb"/><path class="s6i0ky__r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linux-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g75xvebbb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 12V9a7 7 0 1 1 14 0v3c0 1.432.293 2.85.784 4.192q.336.906.762 1.772c.257.528.533 1.046.811 1.564c.182.34.365.68.537 1.025a.997.997 0 0 1-.447 1.341A1 1 0 0 1 21 22H3a1 1 0 0 1-.894-1.447c.172-.345.355-.685.537-1.025c.278-.518.554-1.036.811-1.564q.426-.867.762-1.772C4.707 14.85 5 13.432 5 12");
}

.s6i0ky__r {
  d: path("M10 8h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-4 3h4a1.002 1.002 0 0 1 .707 1.707l-2 2a1 1 0 0 1-1.414 0l-2-2A1 1 0 0 1 10 11M7 21c0-1.306.633-2.546 1.543-3.457C9.454 16.633 10.694 16 12 16c.655 0 1.299.161 1.892.438a5.5 5.5 0 0 1 1.565 1.105C16.367 18.454 17 19.694 17 21a1 1 0 0 1-2 0c0-1.452-1.548-3-3-3s-3 1.548-3 3a1 1 0 0 1-2 0");
}

</style>
