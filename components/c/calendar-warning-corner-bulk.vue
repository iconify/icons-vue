<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mepwg219h"/><path class="bnw30--ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-warning-corner-bulk" /></template>
<style>
.bnw30--ql {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m14 10a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mepwg219h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10h-9a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

</style>
