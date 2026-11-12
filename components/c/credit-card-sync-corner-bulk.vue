<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zv0ky1bfi"/><path class="jvbs2gbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-sync-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jvbs2gbef {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m19 4v3a1 1 0 0 1-.55.893l-.001.001h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2h.748a5 5 0 0 0-.195-.106l-.003-.001a3.473 3.473 0 0 0-4.656 1.554a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.47 5.47 0 0 1 6.316-1.025l.003.001l.004.002q.282.141.546.314V12a1 1 0 0 1 2 0m-8 9.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .963-.999h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894A5.465 5.465 0 0 1 14 21.577");
}

.zv0ky1bfi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7v2H10v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3");
}

</style>
