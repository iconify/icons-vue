<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t473xod8i"/><path class="rs4d5gbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-warning-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rs4d5gbhd {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3 3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-7 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.t473xod8i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
