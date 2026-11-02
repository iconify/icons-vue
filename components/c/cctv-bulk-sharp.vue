<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jbpymwbjb"/><path class="vdyirccfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cctv-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jbpymwbjb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.vdyirccfx {
  d: path("M6 14a6 6 0 1 0 12 0V7a1 1 0 0 1 2 0v7a8 8 0 0 1-16 0V7a1 1 0 0 1 2 0Zm2.315-1.557a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556M12 13h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
