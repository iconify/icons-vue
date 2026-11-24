<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wsk_6w0je"/><path class="yk-aj7w6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooling-tower-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wsk_6w0je {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 9h8a1.002 1.002 0 0 1 .831 1.557c-.301.448-.484.969-.61 1.491A8.3 8.3 0 0 0 16 14c0 1.261.427 2.47 1.095 3.529a9.6 9.6 0 0 0 1.16 1.477q.623.652 1.345 1.194A1 1 0 0 1 19 22H5a1 1 0 0 1-.6-1.8q.722-.542 1.345-1.194a9.6 9.6 0 0 0 1.16-1.477C7.573 16.47 8 15.261 8 14a8.3 8.3 0 0 0-.221-1.952c-.126-.522-.309-1.043-.61-1.491A1 1 0 0 1 8 9");
}

.yk-aj7w6d {
  d: path("M6 6v-.001A3 3 0 0 1 9 3h.001c.651 0 1.279.208 1.799.599A4 4 0 0 1 18 6a1 1 0 0 1-2 0a2 2 0 1 0-4 0a1 1 0 0 1-2 0v-.002A1 1 0 0 0 8 6a1 1 0 0 1-2 0m15 16H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2");
}

</style>
