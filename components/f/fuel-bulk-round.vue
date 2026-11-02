<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k-r8gbbdj"/><path class="k63ox-g2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuel-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k-r8gbbdj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.k63ox-g2n {
  d: path("M15 11a3 3 0 0 1 3 3v1a1 1 0 0 0 2 0V8c0-.468-.395-.98-.707-1.293l-2-2a.999.999 0 1 1 1.414-1.414l2 2C21.422 6.008 22 6.961 22 8v7a3 3 0 1 1-6 0v-1a.997.997 0 0 0-1-1h-2a1 1 0 0 1 0-2ZM3 8h10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
